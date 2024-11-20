// Check if the game object is accessible
if (typeof game !== "undefined") {
    // Set the coins variable to a very large number
    game.coins = 999999999999999999999999999999999999999999999999999999999999999999999;  // Replace this with your desired number

    // Assuming there's a function to update the UI or refresh the coin count
    game.updateCoins();  // This will vary depending on how the game refreshes the UI.

    // Log the new coin count to the console
    console.log("New coin count: " + game.coins);
} else {
    console.log("Game object not found. Ensure you're in a valid game session.");
}
