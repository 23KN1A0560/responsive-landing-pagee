# responsive-landing-pagee
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Responsive Landing Page</title>
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      background: #f9f9f9;
    }

    header {
      background: #4a90e2;
      color: white;
      padding: 20px 0;
      text-align: center;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 20px;
      padding: 10px 0;
      background-color: #357ab7;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    .hero {
      display: flex;
      flex-direction: column;
      align-items: center;
      padding: 60px 20px;
      text-align: center;
      background: #fff;
    }

    .hero h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
      color: #333;
    }

    .hero p {
      max-width: 600px;
      font-size: 1.2rem;
      color: #666;
    }

    .btn {
      margin-top: 30px;
      padding: 12px 24px;
      background-color: #4a90e2;
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      font-size: 1rem;
    }

    .btn:hover {
      background-color: #357ab7;
    }

    footer {
      background: #333;
      color: white;
      
