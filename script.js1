// Function to show the pop-up window
function showPopup(content) {
    const popup = document.getElementById('popup');
    const popupContent = document.getElementById('popup-content');
    popupContent.innerText = content;
    popup.style.display = 'block';
    setTimeout(function() {
        popup.style.display = 'none';
    }, 2000);
}

// Event listener for button clicks
document.addEventListener('DOMContentLoaded', function() {
    const buttons = document.getElementsByTagName('button');
    for (let i = 0; i < buttons.length; i++) {
        buttons[i].addEventListener('click', function() {
            const buttonText = buttons[i].innerText;
            const firstLetter = buttonText.charAt(0);
            showPopup(firstLetter);
            
            // Display the letter in the current window
            document.write('<h1>' + firstLetter + '</h1>');
        });
    }
});
