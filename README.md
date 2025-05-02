<!DOCTYPE html><html lang="bn">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Dreams-Luxury</title>
  <style>
    body { font-family: Arial; margin: 0; padding: 0; background: #f9f9f9; }
    header { background: #222; color: white; padding: 20px; text-align: center; }
    section { padding: 20px; }
    .product { border: 1px solid #ccc; padding: 15px; margin-bottom: 15px; background: white; }
    .product img { max-width: 100%; height: auto; }
    form { display: flex; flex-direction: column; gap: 10px; margin-top: 10px; }
    input, textarea, button { padding: 10px; font-size: 16px; }
    .chat-button { position: fixed; bottom: 20px; right: 20px; background: #25D366; color: white; padding: 15px; border-radius: 50%; text-align: center; text-decoration: none; font-size: 20px; }
  </style>
</head>
<body>
  <header>
    <h1>Dreams-Luxury</h1>
    <p>আপনার স্বপ্নের প্রোডাক্ট এখন আপনার হাতে</p>
  </header>  <section>
    <h2>আমাদের সম্পর্কে</h2>
    <p>Dreams-Luxury একটি প্রিমিয়াম প্রোডাক্ট সরবরাহকারী প্রতিষ্ঠান যেখানে আপনি পাবেন মানসম্মত ও স্টাইলিশ পণ্য।</p>
  </section>  <section>
    <h2>আমাদের প্রোডাক্টসমূহ</h2><div class="product">
  <h3>Luxury Handbag</h3>
  <img src="https://via.placeholder.com/400x200" alt="Handbag" />
  <p>দারুন ডিজাইনের হ্যান্ডব্যাগ, স্টাইল ও কোয়ালিটি নিশ্চিত।</p>
  <form onsubmit="submitOrder(event)">
    <input type="text" name="name" placeholder="আপনার নাম" required />
    <input type="text" name="address" placeholder="আপনার ঠিকানা" required />
    <input type="tel" name="phone" placeholder="ফোন নম্বর" required />
    <button type="submit">অর্ডার করুন</button>
  </form>
</div>

<!-- আরও প্রোডাক্ট এখানে অ্যাড করা যাবে -->

  </section><a class="chat-button" href="https://wa.me/8801841424064" target="_blank">Chat</a>

  <script>
    function submitOrder(event) {
      event.preventDefault();
      alert("আপনার অর্ডার গ্রহণ করা হয়েছে! আমরা খুব শীঘ্রই আপনার সাথে যোগাযোগ করবো।");
      event.target.reset();
      // ভবিষ্যতে এখানে অর্ডার সার্ভারে পাঠানো হবে
    }
  </script></body>
</html>
