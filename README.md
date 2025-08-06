<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>golden506 — Chat</title>
  <link rel="stylesheet" href="styles.css" />
</head>
<body>
  <main class="container">
    <header class="header">
      <h1 id="bot-name">golden506</h1>
      <p id="bot-desc">A friendly assistant that answers like ArmelBot.</p>
    </header>

    <section id="chat" class="chat">
      <div id="messages" class="messages"></div>
    </section>

    <form id="input-form" class="input-form">
      <button type="button" id="voice-btn" title="Use voice">🎤</button>
      <input id="prompt" autocomplete="off" placeholder="Type a message..." />
      <button id="send-btn" type="submit">Send</button>
    </form>
  </main>

  <script src=
