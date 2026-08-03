<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Share Page</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      background-color: #f4f4f9;
      margin: 0;
    }
    .card {
      background: #ffffff;
      padding: 2rem;
      border-radius: 12px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.1);
      text-align: center;
    }
    .share-btn {
      display: inline-block;
      margin: 8px;
      padding: 10px 20px;
      color: #fff;
      background-color: #007bff;
      border: none;
      border-radius: 6px;
      text-decoration: none;
      font-weight: bold;
      cursor: pointer;
    }
    .share-btn.twitter { background-color: #1da1f2; }
    .share-btn.linkedin { background-color: #0077b5; }
  </style>
</head>
<body>

  <div class="card">
    <h2>Share This Page</h2>
    <p>Spread the word on your favorite platforms!</p>
    
    <a class="share-btn twitter" href="https://twitter.com/intent/tweet?text=Check%20this%20out!" target="_blank">Share on X (Twitter)</a>
    <a class="share-btn linkedin" href="https://www.linkedin.com/sharing/share-offsite/?url=https://example.com" target="_blank">Share on LinkedIn</a>
  </div>

</body>
</html>



