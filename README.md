# Bricksville-District-website
welcome 
Join our community https://steamcommunity.com/chat/invite/IegHA1XP
<img width="1365" height="718" alt="image" src="https://github.com/user-attachments/assets/557d2160-823b-41c6-9cea-92d129f44858" />
<img width="492" height="331" alt="plane" src="https://github.com/user-attachments/assets/8f743895-6098-43f6-8553-a775ffc832ed" />
we have alot of members and stuff feel free to join the community and the brickrigs server:)

<img width="165" height="165" alt="image" src="https://github.com/user-attachments/assets/98a9bb67-7c8a-4ac3-8b8f-ad76c44b811d" /> this our 2nd admin
<img width="166" height="163" alt="image" src="https://github.com/user-attachments/assets/64f6485b-5930-4e45-ba4a-422026da973d" /> this is staff 
there is more but im to lazy for that

If you wanna unban request here and text in the gc then send a  pic of the request it might download but remove it after
(https://github.com/user-attachments/files/22694305/unban-request_Version3.html)
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Unban Request Form</title>
  <style>
    body { font-family: Arial, sans-serif; background: #f7f7f7; }
    .container { max-width: 500px; margin: 40px auto; padding: 20px; background: #fff; border-radius: 8px; box-shadow: 0 4px 12px rgba(0,0,0,0.09);}
    h2 { text-align: center; }
    label { display: block; margin-top: 15px; font-weight: bold; }
    input, textarea { width: 100%; padding: 8px; margin-top: 6px; border-radius: 4px; border: 1px solid #ccc; }
    textarea { resize: vertical; }
    button { margin-top: 20px; padding: 12px 24px; background: #4CAF50; color: #fff; border: none; border-radius: 4px; cursor: pointer; width: 100%; }
    button:hover { background: #45a049; }
    #result-message { color: green; text-align: left; margin-top: 20px; display: none; background: #e6ffe6; padding: 15px; border-radius: 4px;}
  </style>
</head>
<body>
  <div class="container">
    <h2>Unban Request</h2>
    <form id="unbanForm" action="#" method="POST">
      <label for="username">Steam Username</label>
      <input type="text" id="username" name="username" required>

      <label for="reason">Reason for Ban</label>
      <input type="text" id="reason" name="reason" required>

      <label for="banned_when_where">When/Where Were You Banned?</label>
      <input type="text" id="banned_when_where" name="banned_when_where" placeholder="e.g., 2025-09-15 on Steam Group" required>

      <label for="appeal">Appeal Message</label>
      <textarea id="appeal" name="appeal" rows="5" placeholder="Explain why you should be unbanned..." required></textarea>

      <button type="submit">Submit Unban Request</button>
    </form>
    <div id="result-message"></div>
  </div>
  <script>
    document.getElementById('unbanForm').addEventListener('submit', function(event) {
      event.preventDefault();
      // Get form values
      const username = document.getElementById('username').value;
      const reason = document.getElementById('reason').value;
      const bannedWhere = document.getElementById('banned_when_where').value;
      const appeal = document.getElementById('appeal').value;
      // Create result message
      const message = `
        <strong>Your Unban Request:</strong><br>
        <strong>Steam Username:</strong> ${username}<br>
        <strong>Reason for Ban:</strong> ${reason}<br>
        <strong>Banned When/Where:</strong> ${bannedWhere}<br>
        <strong>Appeal Message:</strong> ${appeal}
      `;
      document.getElementById('result-message').innerHTML = message;
      document.getElementById('result-message').style.display = 'block';
      this.style.display = 'none'; // Hide form after submit
    });
  </script>
</body>
</html>
