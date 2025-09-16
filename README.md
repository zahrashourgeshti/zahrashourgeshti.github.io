<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>README - HippoPlus</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #0B3C5D;
            --secondary: #D4AF37;
            --accent: #328CC1;
            --light: #F2F2F2;
            --dark: #1D2731;
        }
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }
        
        body {
            background-color: #f8f9fa;
            color: #333;
            line-height: 1.6;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(135deg, var(--primary), var(--dark));
            color: white;
            padding: 40px 20px;
            text-align: center;
            border-bottom: 5px solid var(--secondary);
        }
        
        header h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        header p {
            font-size: 1.2rem;
            opacity: 0.9;
        }
        
        .readme-section {
            background: white;
            border-radius: 10px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
            padding: 30px;
            margin-top: -30px;
            position: relative;
        }
        
        .readme-header {
            border-bottom: 2px solid var(--light);
            padding-bottom: 20px;
            margin-bottom: 30px;
        }
        
        .readme-content {
            line-height: 1.8;
        }
        
        .readme-content h2 {
            color: var(--primary);
            margin: 25px 0 15px;
            padding-bottom: 10px;
            border-bottom: 1px solid var(--light);
        }
        
        .readme-content h3 {
            color: var(--accent);
            margin: 20px 0 10px;
        }
        
        .readme-content p {
            margin-bottom: 15px;
        }
        
        .readme-content ul, .readme-content ol {
            margin: 15px 0;
            padding-left: 20px;
        }
        
        .readme-content li {
            margin-bottom: 8px;
        }
        
        .code-block {
            background: #2D2D2D;
            color: #f8f8f2;
            padding: 15px;
            border-radius: 5px;
            margin: 15px 0;
            overflow-x: auto;
            font-family: 'Courier New', monospace;
        }
        
        .info-box {
            background: #e8f4fd;
            border-left: 4px solid var(--accent);
            padding: 15px;
            margin: 20px 0;
            border-radius: 0 5px 5px 0;
        }
        
        .btn {
            display: inline-block;
            background: var(--primary);
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: 500;
            transition: all 0.3s;
            margin-top: 10px;
        }
        
        .btn:hover {
            background: var(--accent);
            transform: translateY(-2px);
        }
        
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            color: #666;
            font-size: 0.9rem;
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 15px;
            }
            
            header {
                padding: 30px 15px;
            }
            
            header h1 {
                font-size: 2rem;
            }
            
            .readme-section {
                padding: 20px;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>ByonPlus By Zahra Shourgeshti</h1>
        <p>README - Project Guide</p>
    </header>
    
    <div class="container">
        <section class="readme-section">
            <div class="readme-header">
                <h2>About This Project</h2>
            </div>
            
            <div class="readme-content">
                <h2>Hello!</h2>
                <p>My name is Zahra Shourgeshti, and I am a high school student passionate about biology, neuroscience, and related fields.</p>
                
                <h2>Purpose of This Repository</h2>
                <p>The purpose of creating this repository is to deepen my knowledge, share my learning journey, and connect with people who share similar interests.</p>
                
                <div class="info-box">
                    <p><strong>Note:</strong> The projects and notes I publish here reflect parts of my learning path and personal experiences.</p>
                </div>
                
                <h2>Collaboration and Suggestions</h2>
                <p>I would be grateful for any suggestions, feedback, or resources that could help me grow and learn more.</p>
                
                <h2>Scientific Journey</h2>
                <p>This scientific journey is just the beginning for me, but I hope to take greater steps alongside others and contribute to the promotion of science.</p>
                
                <h2>Contact Information</h2>
                <p>You can reach me via email:</p>
                <div class="code-block">
                    zshourgeshti@gmail.com
                </div>
                
                <a href="#" class="btn">Return to Homepage</a>
            </div>
        </section>
    </div>
    
    <footer>
        <p>© 2025 ByonPlus By Zahra Shourgeshti. All rights reserved.</p>
    </footer>
</body>
</html>
