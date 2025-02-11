const questions = [
    { question: "Which position do you prefer to play?", options: ["Point Guard", "Shooting Guard", "Small Forward", "Power Forward", "Center"] },
    { question: "What is your strongest skill?", options: ["Shooting", "Passing", "Defense", "Rebounding", "Speed"] },
    { question: "What is your weakest area?", options: ["Shooting", "Passing", "Defense", "Rebounding", "Speed"] },
    { question: "How do you handle pressure?", options: ["Stay calm and focused", "Get aggressive", "Look for support from teammates", "Take a step back and assess", "Stay confident and positive"] },
    { question: "What's your favorite part of the game?", options: ["Scoring", "Assisting", "Defending", "Rebounding", "Running fast breaks"] },
    { question: "How would you describe your leadership style?", options: ["Lead by example", "Vocal leader", "Supportive leader", "Strategic thinker", "Motivational speaker"] },
    { question: "How do you prepare for a game?", options: ["Watch game film", "Practice hard", "Mentally focus", "Get plenty of rest", "Stay relaxed"] },
    { question: "What's your favorite type of play?", options: ["Pick and roll", "Isolation", "Fast break", "Post-up", "Off-ball movement"] },
    { question: "How do you react to a bad call?", options: ["Complain to the referee", "Stay calm", "Encourage teammates", "Focus on the next play", "Show frustration"] },
    { question: "What motivates you the most?", options: ["Winning", "Improving skills", "Team success", "Personal stats", "Love for the game"] },
    { question: "How do you handle a loss?", options: ["Stay positive", "Analyze mistakes", "Encourage teammates", "Train harder", "Feel down"] },
    { question: "What's your favorite defensive tactic?", options: ["Stealing the ball", "Blocking shots", "Defensive rebounding", "Staying in front of the opponent", "Help defense"] },
    { question: "How important is teamwork to you?", options: ["Extremely important", "Very important", "Somewhat important", "Not very important", "Not important at all"] },
    { question: "What's your favorite type of shot?", options: ["Three-pointer", "Mid-range jumper", "Layup", "Free throw", "Dunk"] },
    { question: "How do you handle criticism?", options: ["Take it positively", "Feel discouraged", "Use it to improve", "Ignore it", "Defend yourself"] },
    { question: "What's your preferred pace of play?", options: ["Fast-paced", "Moderate-paced", "Slow-paced", "Controlled", "Adaptable"] },
    { question: "How do you contribute to your team's success?", options: ["Scoring", "Playmaking", "Defending", "Rebounding", "Leadership"] },
    { question: "What's your favorite off-court activity?", options: ["Training", "Watching games", "Spending time with family", "Relaxing", "Community service"] },
    { question: "How do you stay in shape during the offseason?", options: ["Intensive training", "Light workouts", "Playing other sports", "Rest and recovery", "Balanced approach"] },
    { question: "What's your reaction to a teammate's mistake?", options: ["Encourage them", "Get frustrated", "Give advice", "Ignore it", "Support them"] },
    { question: "How do you handle double teams?", options: ["Pass the ball", "Take the shot", "Drive to the basket", "Call for a screen", "Stay calm and composed"] },
    { question: "What's your favorite way to celebrate a win?", options: ["Party with teammates", "Celebrate with family", "Reflect on the game", "Plan for the next game", "Stay humble"] },
    { question: "How do you handle trash talk from opponents?", options: ["Ignore it", "Talk back", "Use it as motivation", "Stay focused", "Show confidence"] },
    { question: "What's your favorite type of pass?", options: ["No-look pass", "Bounce pass", "Alley-oop", "Chest pass", "Overhead pass"] },
    { question: "How do you handle being benched?", options: ["Stay positive", "Feel frustrated", "Support teammates", "Work harder", "Ask for feedback"] },
    { question: "What's your approach to training?", options: ["Intensive and focused", "Balanced and consistent", "Relaxed and easy-going", "Strategic and planned", "Motivational and enthusiastic"] },
    { question: "How important is it for you to win championships?", options: ["Extremely important", "Very important", "Somewhat important", "Not very important", "Not important at all"] },
    { question: "What's your favorite type of defense?", options: ["Man-to-man", "Zone defense", "Full-court press", "Half-court trap", "Switching defense"] },
    { question: "How do you handle a big lead?", options: ["Stay focused", "Relax and enjoy", "Encourage teammates", "Maintain intensity", "Celebrate early"] },
    { question: "What's your preferred way to score?", options: ["Driving to the basket", "Shooting from distance", "Posting up", "Cutting to the basket", "Free throws"] },
    { question: "How do you react to a teammate's success?", options: ["Celebrate with them", "Feel proud", "Encourage them", "Stay humble", "Stay focused"] },
    { question: "What's your favorite way to warm up before a game?", options: ["Shooting drills", "Passing drills", "Defensive drills", "Stretching", "Mental preparation"] },
    { question: "How do you handle a tough opponent?", options: ["Stay confident", "Adjust strategy", "Work harder", "Support teammates", "Stay focused"] },
    { question: "What's your favorite basketball move?", options: ["Crossover", "Spin move", "Step-back jumper", "Euro step", "Fadeaway jumper"] },
    { question: "How do you handle a shooting slump?", options: ["Keep shooting", "Focus on other skills", "Stay positive", "Practice more", "Take a break"] },
    { question: "What's your favorite type of rebound?", options: ["Offensive rebound", "Defensive rebound", "Put-back", "Tip-in", "Box-out rebound"] },
    { question: "How do you handle a game-winning shot opportunity?", options: ["Take the shot", "Pass to a teammate", "Stay calm and focused", "Look for a good play", "Stay confident"] },
    { question: "What's your favorite type of assist?", options: ["No-look pass", "Alley-oop", "Bounce pass", "Cross-court pass", "Behind-the-back pass"] },
    { question: "How do you handle a losing streak?", options: ["Stay positive", "Analyze mistakes", "Encourage teammates", "Train harder", "Stay focused"] },
    { question: "What's your favorite type of block?", options: ["Chase-down block", "Swat block", "Tip block", "Clean block", "Defensive block"] },
    { question: "How do you handle a clutch situation?", options: ["Stay calm and focused", "Take charge", "Support teammates", "Look for the best play", "Stay confident"] },
    { question: "What's your favorite type of celebration?", options: ["High-fives", "Chest bumps", "Dance moves", "Pointing to the crowd", "Staying humble"] },
    { question: "How do you handle a physical game?", options: ["Stay aggressive", "Stay calm", "Encourage teammates", "Adjust strategy", "Stay focused"] },
    { question: "What's your favorite type of steal?", options: ["On-ball steal", "Passing lane steal", "Double-team steal", "Pickpocket steal", "Help defense steal"] },
    { question: "How do you handle a big stage?", options: ["Stay focused", "Stay calm", "Encourage teammates", "Stay confident", "Stay humble"] },
    { question: "What's your favorite type of game?", options: ["Close game", "Blowout win", "Comeback win", "Defensive battle", "High-scoring game"] },
    { question: "How do you handle a bad game?", options: ["Stay positive", "Analyze mistakes", "Encourage teammates", "Train harder", "Stay focused"] },
    { question: "What's your favorite type of basketball shoe?", options: ["High-top", "Low-top", "Mid-top", "Retro", "Signature"] },
];

const playerDescriptions = {
    "Keegan Murray": "Keegan Murray is known for his versatility and strong defensive skills. He excels at both ends of the court.",
    "LeBron James": "LeBron James is a dominant all-around player with exceptional passing, scoring, and leadership abilities.",
    "Steph Curry": "Steph Curry is renowned for his incredible shooting accuracy and ability to create plays from beyond the arc.",
    "Trae Young": "Trae Young is an offensive powerhouse with excellent ball-handling skills and a knack for scoring.",
    "Dante Exum": "Dante Exum is a rare talent with a unique combination of size, speed, and playmaking ability."
};

const quizContainer = document.getElementById('quiz');
const resultContainer = document.getElementById('result');
const resultContainerParent = document.getElementById('result-container');

function loadQuiz() {
    questions.forEach((q, index) => {
        const questionDiv = document.createElement('div');
        questionDiv.classList.add('question');
        questionDiv.innerHTML = `<p>${index + 1}. ${q.question}</p>`;

        const optionsList = document.createElement('ul');
        optionsList.classList.add('options');
        q.options.forEach((option, i) => {
            const optionItem = document.createElement('li');
            optionItem.innerHTML = `<input type="radio" name="q${index}" value="${i}">${option}`;
            optionsList.appendChild(optionItem);
        });

        questionDiv.appendChild(optionsList);
        quizContainer.appendChild(questionDiv);
    });
}

function calculateResult() {
    const answers = [];
    questions.forEach((q, index) => {
        const selectedOption = document.querySelector(`input[name="q${index}"]:checked`);
        if (selectedOption) {
            answers.push(parseInt(selectedOption.value));
        } else {
            answers.push(-1); // No answer selected
        }
    });

    const playerScores = {
        "Keegan Murray": 0,
        "LeBron James": 0,
        "Steph Curry": 0,
        "Trae Young": 0,
        "Dante Exum": 0
    };

    answers.forEach(answer => {
        if (answer === 0) playerScores["Keegan Murray"]++;
        else if (answer === 1) playerScores["LeBron James"]++;
        else if (answer === 2) playerScores["Steph Curry"]++;
        else if (answer === 3) playerScores["Trae Young"]++;
        else if (answer === 4) playerScores["Dante Exum"]++;
    });

    let highestScore = -1;
    let mostLikePlayer = "";
    for (const player in playerScores) {
        if (playerScores[player] > highestScore) {
            highestScore = playerScores[player];
            mostLikePlayer = player;
        }
    }

    resultContainer.innerHTML = `You are most like ${mostLikePlayer}<br><br>${playerDescriptions[mostLikePlayer]}`;
    resultContainerParent.style.display = 'block';
    resultContainer.scrollIntoView({ behavior: 'smooth' });
}

loadQuiz();
