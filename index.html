let countdownInterval;
let remainingTime;
let isPaused = false;

document.getElementById('start-btn').addEventListener('click', startTimer);
document.getElementById('pause-btn').addEventListener('click', pauseTimer);
document.getElementById('reset-btn').addEventListener('click', resetTimer);

function startTimer() {
    const minutes = parseInt(document.getElementById('minutes').value) || 0;
    const seconds = parseInt(document.getElementById('seconds').value) || 0;
    
    if (minutes < 0 || seconds < 0 || seconds > 59) {
        alert("Please enter valid minutes and seconds.");
        return;
    }

    if (!isPaused) {
        remainingTime = minutes * 60 + seconds;
    }
    
    countdownInterval = setInterval(updateDisplay, 1000);
}

function updateDisplay() {
    if (remainingTime > 0) {
        remainingTime--;
        const minutes = Math.floor(remainingTime / 60);
        const seconds = remainingTime % 60;
        document.getElementById('timer-display').innerText = 
            `${String(minutes).padStart(2, '0')}:${String(seconds).padStart(2, '0')}`;
    } else {
        clearInterval(countdownInterval);
        document.getElementById('timer-display').innerText = "00:00";
    }
}

function pauseTimer() {
    if (countdownInterval) {
        clearInterval(countdownInterval);
        isPaused = true;
    }
}

function resetTimer() {
    clearInterval(countdownInterval);
    remainingTime = 0;
    isPaused = false;
    document.getElementById('timer-display').innerText = "00:00";
    document.getElementById('minutes').value = "";
    document.getElementById('seconds').value = "";
}
