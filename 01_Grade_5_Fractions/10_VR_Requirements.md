<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VR / 3D Requirements: Grade 5 - Fractions</title>
    <style>
        body { font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; max-width: 900px; margin: 40px auto; padding: 30px; background: #f5f5f5; line-height: 1.6; }
        .container { background: white; padding: 40px; border-radius: 10px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
        h1 { color: #2c3e50; border-bottom: 3px solid #3498db; padding-bottom: 15px; }
        h2 { color: #34495e; margin-top: 30px; border-left: 4px solid #3498db; padding-left: 15px; }
        .back-link { display: inline-block; margin-bottom: 20px; color: #3498db; text-decoration: none; font-weight: bold; }
        .back-link:hover { text-decoration: underline; }
        .requirement-section { background: #f8f9fa; padding: 25px; margin: 20px 0; border-radius: 8px; border-left: 5px solid #3498db; }
        .requirement-section h3 { color: #2c3e50; margin-top: 0; border-bottom: 2px solid #ecf0f1; padding-bottom: 10px; }
        .requirement-item { margin: 12px 0; padding: 12px; background: white; border-radius: 6px; border-left: 3px solid #3498db; }
        .requirement-item strong { color: #3498db; }
        .icon { font-size: 20px; margin-right: 8px; }
        .note { background: #fff3cd; padding: 15px; border-left: 4px solid #ffc107; border-radius: 6px; margin: 15px 0; }
        .success { background: #d4edda; padding: 15px; border-left: 4px solid #28a745; border-radius: 6px; margin: 10px 0; }
        .failure { background: #f8d7da; padding: 15px; border-left: 4px solid #dc3545; border-radius: 6px; margin: 10px 0; }
    </style>
</head>
<body>
    <div class="container">
        <a href="../index.html" class="back-link">← Back to Portfolio</a>
        
        <h1> VR / 3D Requirements: Grade 5 - Fractions</h1>
        
        <div class="requirement-section">
            <h3><span class="icon">🎨</span> 1. 3D Assets Needed</h3>
            <div class="requirement-item">
                <strong>Chocolate Bar:</strong> A realistic 3D model of a chocolate bar, clearly divided into 8 equal, separable squares.
            </div>
            <div class="requirement-item">
                <strong>Virtual Plate:</strong> A simple, clean plate to hold the grabbed pieces.
            </div>
            <div class="requirement-item">
                <strong>Environment:</strong> A cozy, well-lit virtual kitchen table (low poly for performance, but visually appealing).
            </div>
        </div>

        <div class="requirement-section">
            <h3><span class="icon"></span> 2. Required Interactions</h3>
            <div class="requirement-item">
                <strong>Grab & Drop:</strong> The student must be able to use VR controllers to grab individual chocolate squares and drop them onto the plate.
            </div>
            <div class="requirement-item">
                <strong>Snap-to-Grid:</strong> When a square is dropped near the plate, it should "snap" into a neat row to make counting easy.
            </div>
            <div class="requirement-item">
                <strong>Highlighting:</strong> Specific squares must glow (e.g., yellow for the student's pieces, blue for the friend's pieces) to guide the student's attention.
            </div>
        </div>

        <div class="requirement-section">
            <h3><span class="icon"></span> 3. UI / UX Elements</h3>
            <div class="requirement-item">
                <strong>Floating Text:</strong> Minimalist, easy-to-read text for instructions and feedback (e.g., "You ate 2/8").
            </div>
            <div class="requirement-item">
                <strong>VR Pointer:</strong> A laser pointer originating from the controller for selecting multiple-choice answers.
            </div>
            <div class="requirement-item">
                <strong>Feedback Visuals:</strong>
                <div class="success">✅ Success: Green glow around the correct answer + simple confetti particle effect.</div>
                <div class="failure">❌ Failure: Gentle red outline + a subtle "try again" sound.</div>
            </div>
        </div>

        <div class="requirement-section">
            <h3><span class="icon">🔊</span> 4. Audio Requirements</h3>
            <div class="requirement-item">
                <strong>Narrator Voice:</strong> Friendly, encouraging, and clear (Arabic or English depending on the target curriculum).
            </div>
            <div class="requirement-item">
                <strong>Sound Effects (SFX):</strong>
                <ul>
                    <li>"Pop" or "Click" sound when grabbing a chocolate piece.</li>
                    <li>"Snap" sound when placing it on the plate.</li>
                    <li>Positive chime for correct answers.</li>
                </ul>
            </div>
        </div>

        <div class="requirement-section">
            <h3><span class="icon">️</span> 5. Technical Constraints & Notes</h3>
            <div class="requirement-item">
                <strong>Performance:</strong> Models should be optimized for standalone VR headsets (e.g., Meta Quest).
            </div>
            <div class="note">
                <strong> Accessibility:</strong> Text should be large enough to read comfortably in VR. Color choices for highlighting should be colorblind-friendly (e.g., using patterns or distinct brightness, not just red/green).
            </div>
        </div>
    </div>
</body>
</html>
