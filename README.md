<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Symbolic Records Music Player</title>
  <style>
    body {
      background-color: #121212;
      color: #e53935;
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 20px;
      display: flex;
      flex-direction: column;
      align-items: center;
    }
    h1 {
      margin-bottom: 30px;
      text-align: center;
      font-weight: bold;
    }
    .track-list {
      width: 100%;
      max-width: 600px;
      background-color: #1e1e1e;
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 0 10px #e53935aa;
    }
    .track {
      margin-bottom: 20px;
    }
    .track:last-child {
      margin-bottom: 0;
    }
    audio {
      width: 100%;
      outline: none;
      border-radius: 4px;
      background-color: #333;
    }
    footer {
      margin-top: 40px;
      font-size: 0.9em;
      color: #777;
    }
    @media (max-width: 600px) {
      body {
        padding: 10px;
      }
      .track-list {
        padding: 15px;
      }
    }
  </style>
</head>
<body>
  <h1>Symbolic Records Music Player</h1>
  <div class="track-list">
    <div class="track">
      <strong>PANDA - KALHIRAVA</strong>
      <audio controls>
        <source src="https://soundcloud.com/symbolicrecordsmv/panda-kalhirava" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
    <div class="track">
      <strong>Heelaanamey [Prod. Reaper]</strong>
      <audio controls>
        <source src="https://soundcloud.com/symbolicrecordsmv/heelaanamey-prod-reaper" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
    <div class="track">
      <strong>Hunnamey ft. Dewin [Prod. Shahu Wayne]</strong>
      <audio controls>
        <source src="https://soundcloud.com/symbolicrecordsmv/hunnamey-ft-dewin-prod-shahu-wayne" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
    <div class="track">
      <strong>Lifaafaa ft. Pest [Prod. Shahu Wayne]</strong>
      <audio controls>
        <source src="https://soundcloud.com/symbolicrecordsmv/lifaafaa-ft-pest-prod-shahu-wayne" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
    <div class="track">
      <strong>Uvaalaadhanee ft. Maatu</strong>
      <audio controls>
        <source src="https://soundcloud.com/symbolicrecordsmv/uvaalaadhanee-ft-maatu" type="audio/mpeg" />
        Your browser does not support the audio element.
      </audio>
    </div>
  </div>
  <footer>© 2025 Symbolic Records</footer>
</body>
</html>
