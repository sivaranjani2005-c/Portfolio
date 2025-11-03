<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <style>
    /* ---------- BASIC STYLES ---------- */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: "Poppins", sans-serif;
    }
    body {
      background: #f5f7fa;
      color: #333;
      scroll-behavior: smooth;
    }
    header {
      position: fixed;
      width: 100%;
      background: #111;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 100;
    }
    header h1 {
      color: #fff;
      font-size: 24px;
    }
    nav a {
      color: #fff;
      margin: 0 15px;
      text-decoration: none;
      font-size: 16px;
      transition: 0.3s;
    }
    nav a:hover {
      color: #00bcd4;
    }

    /* ---------- SECTIONS ---------- */
    section {
      padding: 100px 60px;
      min-height: 100vh;
    }

    /* ---------- HOME ---------- */
    #home {
      display: flex;
      justify-content: center;
      align-items: center;
      flex-direction: column;
      background: linear-gradient(135deg, #00bcd4, #2196f3);
      color: white;
      text-align: center;
    }
    #home h2 {
      font-size: 48px;
      margin-bottom: 10px;
    }
    #home p {
