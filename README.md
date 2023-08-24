<!DOCTYPE html>
<html lang="en">
<head>
</head>
<body>
    <h1>Magic Internet Money Payment System</h1>
    <p>Welcome to the Magic Internet Money Payment System! This project demonstrates a basic working knowledge of Bitcoin and the Lightning Network by building a simple application for accepting payments and providing confirmation to the user.</p>
    <h2>Getting Started</h2>
    <p>Follow these steps to set up and run the project:</p>
    <ol>
        <li>Clone the repository:</li>
        <pre><code>git clone https://github.com/elfeenah/magic-internet-money.git</code></pre>
        <li>Install the required dependencies:</li>
        <pre><code>pip install bitcoinlib</code></pre>
        <li>Run the payment application:</li>
        <pre><code>python payment_app.py</code></pre>
    </ol>
    <h2>Functionality</h2>
    <p>The application generates a Bitcoin address for receiving payments. It then continuously monitors the blockchain for incoming payments to that address. Once a payment is detected, a confirmation message is displayed.</p>
    <h2>Important Notes</h2>
    <p>Remember that this example is for educational purposes and might not include all necessary security measures or edge case handling for a production environment. Be cautious when using real Bitcoin and consider using testnet or signet for development and testing.</p>
    <p>Ensure you have set up a local Bitcoin node or have access to a testnet node to fetch blockchain data. Modify the script to use the appropriate RPC URL for your node.</p>
    <hr>
    <p>This project was created by **Nafisa Lawal Idris**. You can find more of my work on <a href="https://github.com/elfeenah">GitHub</a>.</p>
</body>
</html>
