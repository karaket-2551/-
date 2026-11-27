<!DOCTYPE html>
<html lang="th" translate="no">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="google" content="notranslate">
    <title>E-Portfolio | นางสาวการะเกด หินเกล็ด</title>
    <!-- นำเข้าฟอนต์ Prompt จาก Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Prompt:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        /* ตั้งค่าตัวแปรสีธีม น้ำเงิน - ขาว */
        :root {
            --primary-blue: #1e40af;      /* น้ำเงินเข้มหลัก */
            --secondary-blue: #3b82f6;    /* น้ำเงินสว่าง */
            --light-blue: #eff6ff;        /* ฟ้าอ่อนพื้นหลัง */
            --accent-blue: #dbeafe;       /* ฟ้าอ่อนสำหรับขอบ/ป้าย */
            --text-dark: #1e293b;         /* สีตัวอักษรเข้ม */
            --text-muted: #64748b;        /* สีตัวอักษรรอง */
            --white: #ffffff;
            --shadow: 0 10px 25px -5px rgba(30, 64, 175, 0.1), 0 8px 10px -6px rgba(30, 64, 175, 0.1);
            --transition: all 0.3s ease;
        }

        /* รีเซ็ตและตั้งค่าพื้นฐาน */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Prompt', sans-serif;
            scroll-behavior: smooth;
        }

        body {
            background-color: var(--white);
            color: var(--text-dark);
            line-height: 1.6;
        }

        /* แถบเมนูนำทาง (Navbar) */
        header {
            position: fixed;
            top: 0;
            width: 100%;
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            box-shadow: 0 2px 15px rgba(0, 0, 0, 0.05);
            z-index: 1000;
        }

        .nav-container {
            max-width: 1140px;
            margin: 0 auto;
            padding: 1rem 1.
