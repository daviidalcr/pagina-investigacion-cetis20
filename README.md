<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Investigación: El Impacto del Fentanilo</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&family=Open+Sans:wght@400;600&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary-color: #0f172a;
            --secondary-color: #1e293b;
            --accent-color: #e11d48;
            --text-dark: #334155;
            --text-light: #f8fafc;
            --bg-light: #f1f5f9;
            --card-bg: #ffffff;
            --transition: all 0.3s ease;
        }
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { font-family: 'Open Sans', sans-serif; color: var(--text-dark); background-color: var(--bg-light); line-height: 1.6; }
        h1, h2, h3 { font-family: 'Montserrat', sans-serif; font-weight: 700; }
        header { background-color: rgba(15, 23, 42, 0.95); position: fixed; width: 100%; top: 0; left: 0; z-index: 1000; box-shadow: 0 2px 10px rgba(0,0,0,0.1); backdrop-filter: blur(10px); }
        .navbar { max-width: 1200px; margin: 0 auto; display: flex; justify-content: space-between; align-items: center; padding: 1rem 2rem; }
        .logo { color: var(--text-light); font-size: 1.3rem; display: flex; align-items: center; gap: 10px; }
        .logo span { color: var(--accent-color); }
        .nav-menu { display: flex; list-style: none; gap: 1.5rem; }
        .nav-menu a { color: #cbd5e1; text-decoration: none; font-weight: 600; font-size: 0.9rem; transition: var(--transition); padding: 0.5rem 0.7rem; border-radius: 4px; }
        .nav-menu a:hover, .nav-menu a.active { color: var(--text-light); background-color: var(--accent-color); }
        #hero { background: linear-gradient(135deg, rgba(15, 23, 42, 0.9) 100%, rgba(30, 41, 59, 0.8) 100%), url('https://images.unsplash.com/photo-1584308666744-24d5c474f2ae?q=80&w=1200') no-repeat center center/cover; height: 100vh; display: flex; align-items: center; justify-content: center; text-align: center; color: var(--text-light); padding: 0 1rem; }
        .hero-content { max-width: 800px; animation: fadeIn 1.5s ease; }
        .hero-tag { background-color: var(--accent-color); color: white; padding: 0.4rem 1rem; border-radius: 50px; font-size: 0.85rem; font-weight: 600; text-transform: uppercase; letter-spacing: 1px; display: inline-block; margin-bottom: 1.5rem; }
