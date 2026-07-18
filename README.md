<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TruJet ATR 72-600 Fleet Milestone</title>
    <style>
        :root {
            --primary-blue: #0A3663;
            --accent-orange: #FF6600;
            --neutral-bg: #F4F6F9;
            --card-bg: #FFFFFF;
            --text-dark: #333333;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--neutral-bg);
            color: var(--text-dark);
            margin: 0;
            padding: 20px;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
        }

        .container {
            max-width: 800px;
            width: 100%;
            background: var(--card-bg);
            border-radius: 12px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.08);
            overflow: hidden;
        }

        .header {
            background-color: var(--primary-blue);
            color: #ffffff;
            padding: 24px;
            text-align: center;
            border-bottom: 4px solid var(--accent-orange);
        }

        .header h1 {
            margin: 0;
            font-size: 1.8rem;
            font-weight: 700;
            letter-spacing: 0.5px;
        }

        .header p {
            margin: 8px 0 0 0;
            font-size: 1rem;
            opacity: 0.9;
        }

        .content {
            padding: 24px;
        }

        .video-section {
            margin-bottom: 24px;
        }

        .video-container {
            position: relative;
            padding-bottom: 56.25%; /* 16:9 Aspect Ratio */
            height: 0;
            overflow: hidden;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
            background: #000;
        }

        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            border: 0;
        }

        .specs-section {
            background: #F9FAFB;
            border: 1px solid #E5E7EB;
            border-radius: 8px;
            padding: 20px;
        }

        .specs-section h2 {
            margin-top: 0;
            font-size: 1.3rem;
            color: var(--primary-blue);
            border-bottom: 2px solid #E5E7EB;
            padding-bottom: 8px;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 16px;
            margin-top: 16px;
        }

        .spec-item {
            display: flex;
            flex-direction: column;
        }

        .spec-label {
            font-size: 0.85rem;
            text-transform: uppercase;
            color: #6B7280;
            font-weight: 600;
            letter-spacing: 0.5px;
        }

        .spec-value {
            font-size: 1.1rem;
            color: var(--text-dark);
            font-weight: 700;
            margin-top: 4px;
        }

        @media (max-width: 600px) {
            body { padding: 10px; }
            .header h1 { font-size: 1.5rem; }
            .content { padding: 16px; }
        }
    </style>
</head>
<body>

<div class="container">
    <div class="header">
        <h1>Birth of TruJet NEW ATR 72-600</h1>
        <p>Welcoming the newest addition to the regional connectivity fleet</p>
    </div>

    <div class="content">
        <!-- Flight Simulation Livery Video Context Section -->
        <div class="video-section">
            <div class="video-container">
                <iframe 
                    src="https://youtube.com" 
                    title="MSFS ATR 42/72-600 Liveries" 
                    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" 
                    allowfullscreen>
                </iframe>
            </div>
        </div>

        <!-- Aircraft Specifications Section -->
        <div class="specs-section">
            <h2>Aircraft Specifications (ATR 72-600)</h2>
            <div class="grid">
                <div class="spec-item">
                    <span class="spec-label">Passenger Capacity</span>
                    <span class="spec-value">68 - 78 Seats</span>
                </div>
                <div class="spec-item">
                    <span class="spec-label">Engine Type</span>
                    <span class="spec-value">Pratt & Whitney PW127M</span>
                </div>
                <div class="spec-item">
                    <span class="spec-label">Max Take-Off Power</span>
                    <span class="spec-value">2,750 SHP per engine</span>
                </div>
                <div class="spec-item">
                    <span class="spec-label">Maximum Range</span>
                    <span class="spec-value">900 Nautical Miles</span>
                </div>
            </div>
        </div>
    </div>
</div>

</body>
</html>
