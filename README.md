<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>aizer.fr UI Clone</title>
  <style>
    body {
      background-color: #0d1117;
      color: #c9d1d9;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      height: 100vh;
      margin: 0;
    }
    .card {
      background-color: #161b22;
      border-radius: 10px;
      padding: 20px;
      text-align: center;
      width: 300px;
      box-shadow: 0 0 12px rgba(0,0,0,0.5);
    }
    .avatar {
      width: 60px;
      height: 60px;
      border-radius: 50%;
      object-fit: cover;
    }
    .username {
      font-size: 20px;
      font-weight: bold;
      margin-top: 10px;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 8px;
    }
    .badge {
      background-color: #0e639c;
      color: white;
      font-size: 12px;
      padding: 2px 6px;
      border-radius: 4px;
      display: inline-flex;
      align-items: center;
      gap: 4px;
    }
    .status {
      margin-top: 8px;
      display: flex;
      gap: 8px;
      justify-content: center;
    }
    .status span {
      font-size: 12px;
      padding: 2px 6px;
      border-radius: 4px;
    }
    .offline {
      background-color: #f04747;
      color: white;
    }
    .idle {
      background-color: #faa61a;
      color: black;
    }
    .online {
      background-color: #43b581;
      color: white;
    }
    .activity {
      margin-top: 12px;
      font-style: italic;
      color: #8b949e;
    }
  </style>
</head>
<body>

  <div class="card">
    <img class="avatar" src="your-image-url.png" alt="avatar">
    <div class="username">
      aizer.fr
      <span class="badge">💀 1337</span>
    </div>
    <div class="status">
      <span class="idle">Idle</span>
      <span class="online">Activity Off</span>
    </div>
    <div class="activity">I'm not currently doing anything!</div>
  </div>

</body>
</html>
