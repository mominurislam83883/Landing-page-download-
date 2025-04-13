<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ডিজিটাল ফাইল পেমেন্ট</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f3f4f6;
            padding: 30px;
            max-width: 600px;
            margin: auto;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h2 {
            color: #333;
        }
        label {
            display: block;
            margin: 15px 0 5px;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            border-radius: 5px;
            border: 1px solid #ccc;
        }
        button {
            margin-top: 20px;
            padding: 12px 20px;
            background: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }
        .payment-info {
            background: #f9fafb;
            border: 1px solid #ddd;
            padding: 10px;
            border-radius: 5px;
            margin-bottom: 20px;
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>ফাইল ডাউনলোডের জন্য পেমেন্ট করুন</h2>
        <div class="payment-info">
            <p><strong>বিকাশ:</strong> 01764585744</p>
            <p><strong>নগদ:</strong> 01860468289</p>
            <p><strong>রকেট:</strong> 01860468289</p>
            <p>ফাইলের মূল্য: <strong>৫০ টাকা</strong></p>
        </div>
        <form action="https://formspree.io/f/your-form-id" method="POST">
            <label for="name">আপনার নাম</label>
            <input type="text" name="name" required>
            
            <label for="number">মোবাইল নাম্বার</label>
            <input type="text" name="number" required>
            
            <label for="trxid">পেমেন্টের TRX ID</label>
            <input type="text" name="trxid" required>

            <label for="message">অতিরিক্ত বার্তা (যদি থাকে)</label>
            <textarea name="message" rows="4"></textarea>

            <button type="submit">সাবমিট করুন</button>
        </form>
    </div>
</body>
</html>
