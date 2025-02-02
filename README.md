<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>5-Bit Binary Subtractor</title>
</head>
<body>
    <h1>5-Bit Binary Subtractor</h1>
    <p>This project implements a 5-bit binary subtractor using <strong>Logisim</strong>. It takes two 5-bit binary numbers as inputs, performs binary subtraction, and outputs the result as a decimal and hexadecimal value. The results are displayed on a <strong>7-segment display</strong> for easy viewing. The subtractor also handles negative results (e.g., 1 - 3 outputs -2).</p>
    <h2>Features</h2>
    <ul>
        <li><strong>Input:</strong> Two 5-bit binary numbers.</li>
        <li><strong>Subtraction:</strong> Performs binary subtraction of the two input numbers.</li>
        <li><strong>Output:</strong>
            <ul>
                <li>Displays the result in <strong>decimal</strong> format.</li>
                <li>Displays the result in <strong>hexadecimal</strong> format.</li>
                <li>Handles <strong>negative results</strong> (e.g., 1 - 3 = -2).</li>
                <li>Uses <strong>7-segment displays</strong> to show the results.</li>
            </ul>
        </li>
    </ul>
    <h2>Components Used</h2>
    <ul>
        <li><strong>Logisim:</strong> Used to design the digital circuit and simulate the logic.</li>
        <li><strong>7-Segment Display:</strong> For displaying the results in both decimal and hexadecimal formats.</li>
        <li><strong>Binary Adder/Subtractor Circuit:</strong> The core logic for binary subtraction.</li>
        <li><strong>MUX (Multiplexer):</strong> Used to select between the decimal and hexadecimal outputs for the 7-segment display.</li>
        <li><strong>Decoders:</strong> Used to convert the binary result into a format compatible with the 7-segment display for both decimal and hexadecimal values.</li>
    </ul>
    <h2>How to Use</h2>
    <ol>
        <li>Clone or download this repository to your local machine.</li>
        <li>Open the project in <strong>Logisim</strong>.</li>
        <li>The circuit will have two inputs for the 5-bit binary numbers.</li>
        <li>The output will be shown on the 7-segment displays, representing the subtraction result in both decimal and hexadecimal formats.</li>
    </ol>
    <h2>Example</h2>
    <h3>Negative Output Example:</h3>
    <p><strong>Input A:</strong> 00001 (binary)</p>
    <p><strong>Input B:</strong> 00011 (binary)</p>
    <h3>Output:</h3>
    <p><strong>Decimal Result:</strong> -2</p>
    <p><strong>Hexadecimal Result:</strong> -2</p>
    <h2>Installation</h2>
    <ol>
        <li><strong>Download Logisim:</strong> <a href="https://sourceforge.net/projects/circuit/">Logisim on SourceForge</a>.</li>
        <li><strong>Install Logisim</strong> following the instructions on the page.</li>
        <li><strong>Clone or Download</strong> this repository.</li>
        <li><strong>Open the project</strong> (.circ file) in Logisim.</li>
    </ol>
</body>
</html>
