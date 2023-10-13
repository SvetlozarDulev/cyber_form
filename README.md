
<svg fill="none" viewBox="0 0 800 400" width="800" height="400" xmlns="http://www.w3.org/2000/svg">
  <foreignObject width="100%" height="100%">
    <html xmlns="http://www.w3.org/1999/xhtml">
      <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>A Cybersecurity Attitudes Survey</title>
        <link rel="stylesheet" href="style.css">
        <style>
          * {
            padding: 0;
            margin: 0;
            box-sizing: border-box;
            font: 16px/1.2 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
          }
          body {
            background: linear-gradient(270deg, #c83d92, #c8bf3d);
            margin: 0 30em;
            min-height: 100vh;
            width: 70%;
            display: flex;
            justify-content: center;
            flex-direction: column;
          }
          header {
            text-align: center;
            border-bottom: 2px solid red;
            margin-bottom: 30px;
            padding-bottom: 5px;
            width: 60%;
          }
          h1 {
            padding: 1em;
            font-size: 2em;
          }
          p {
            font-weight: bold;
            font-size: 1.5em;
          }
          form {
            display: flex;
            flex-direction: column;
            width: 60%;
            background: linear-gradient(270deg, #e9796a, #d6c66c);
            padding: 1em;
            border-radius: 0.3em;
          }
          .label, legend {
            padding: 0.5em;
            font-weight: bold;
          }
          .text, .downmenu {
            width: 100%;
            height: 2.35em;
            border-radius: 0.3em;
            padding: 0.5em;
          }
          .right {
            text-align: right;
          }
          button {
            margin-top: 5px;
            display: block;
            background: rgb(17, 196, 17);
            border: 1px solid white;
            color: white;
            padding: 0.75rem;
            width: 100%;
            font-size: 20px;
            position: relative;
            overflow: hidden;
            border-radius: 4px;
          }
          button:hover {
            font-size: 28px;
            box-shadow: 1px 1px 30px rgb(0, 0, 0);
          }
          .choices {
            display: flex;
            flex-direction: column;
            row-gap: 0.5em;
            padding-left: 0.5em;
            padding-bottom: 0.8em;
          }
          div {
            width: 100%;
            margin-bottom: 8px;
          }
          textarea {
            width: 100%;
          }
          .right-align {
            margin-right: 5px;
          }
          @media (max-width: 768px) {
            body {
              margin: 0 1em;
              width: 90%;
            }
            header {
              width: 90%;
            }
            form {
              width: 90%;
            }
          }
        </style>
      </head>
      <body>
        <header>
          <h1>Protecting Digital Lives: A Cybersecurity Attitudes Survey</h1>
          <p>Exploring Public Attitudes and Perceptions Towards Online Security</p>
        </header>
        <main>
          <form method="post">
            <div>
              <label for="name" class="label font">Name</label>
              <input type="text" placeholder="Enter your name" class="text">
            </div>
            <!-- Add your form fields and content here -->
            <div>
              <button type="submit">Submit</button>
            </div>
          </form>
        </main>
      </body>
    </html>
  </foreignObject>
</svg>
