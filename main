// Functions for timers for each challenge
function timerOne() {
  var seconds = 20;
  timedLoop(1000, function() {
    seconds--;
    console.log(seconds + " seconds left");
    setText("secondcounterOne", seconds);
    if(seconds == 0) {
      setScreen("failScreen");
    }
  });
}

function timerTwo() {
  var seconds = 25;
  timedLoop(1000, function() {
    seconds--;
    console.log(seconds + " seconds left");
    setText("secondcounterTwo", seconds);
    if(seconds == 0) {
      setScreen("failScreen");
    }
  });
}

function timerThree() {
  var seconds = 35;
  timedLoop(1000, function() {
    seconds--;
    console.log(seconds + " seconds left");
    setText("secondcounterThree", seconds);
    if(seconds == 0) {
      setScreen("failScreen");
    }
  });
}

function timerFour() {
  var seconds = 45;
  timedLoop(1000, function() {
    seconds--;
    console.log(seconds + " seconds left");
    setText("secondcounterFour", seconds);
    if(seconds == 0) {
      setScreen("failScreen");
    }
  });
}

function timerFive() {
  var seconds = 50;
  timedLoop(1000, function() {
    seconds--;
    console.log(seconds + " seconds left");
    setText("secondcounterFive", seconds);
    if(seconds == 0) {
      setScreen("failScreen");
    }
  });
}

function timerSix() {
  var seconds = 60;
  timedLoop(1000, function() {
    seconds--;
    console.log(seconds + " seconds left");
    setText("secondcounterSix", seconds);
    if(seconds == 0) {
      setScreen("failScreen");
    }
  });
}

function timerSeven() {
  var seconds = 70;
  timedLoop(1000, function() {
    seconds--;
    console.log(seconds + " seconds left");
    setText("secondcounterSeven", seconds);
    if(seconds == 0) {
      setScreen("failScreen");
    }
  });
}

function timerEight() {
  var seconds = 80;
  timedLoop(1000, function() {
    seconds--;
    console.log(seconds + " seconds left");
    setText("secondcounterEight", seconds);
    if(seconds == 0) {
      setScreen("failScreen");
    }
  });
}

// Function for clearing input boxes
function clearInputBoxes() {
  setText("inputOne", "");
  setText("inputTwo", "");
  setText("inputThree", "");
  setText("inputFour", "");
  setText("inputFive", "");
  setText("inputSix", "");
  setText("inputSeven", "");
  setText("inputEight", "");
}

// Button for how to play screen
onEvent("howtoplayButton", "click", function( ) {
  setScreen("howtoplayScreen");
});

// Button to return to menu screen from how to play screen screen
onEvent("menuButton", "click", function( ) {
  setScreen("menuScreen");
});

// Button to continue on to play screen
onEvent("contButton", "click", function( ) {
  setScreen("playScreen");
});

//Button to return to menu screen from winning screen
onEvent("menuButtonTwo", "click", function( ) {
  setScreen("menuScreen");
  clearInputBoxes();
});

// Button to restart the game if you failed
onEvent("restartButton", "click", function( ) {
  stopTimedLoop();
  setScreen("menuScreen");
  clearInputBoxes();
});

// Button to start the game
onEvent("playButton", "click", function( ) {
  setScreen("challengeOne");
  timerOne();
  // Checking answer for challenge one
  onEvent("challengeOne", "keydown", function(event) {
    if(event.key=="Enter"){
      var inputOne = getText("inputOne");
      if(inputOne=="You can lead a horse to water but you can't make him drink."){
        stopTimedLoop();
        setScreen("challengeTwo");
        timerTwo();
      }
      else{
        setScreen("failScreen");
      }
    }
  });
  // Checking answer for challenge two
  onEvent("challengeTwo", "keydown", function(event) {
    if(event.key=="Enter"){
      var inputTwo = getText("inputTwo");
      if(inputTwo=="Please take your dog, Cali, out for a walk. He really needs some exercise!"){
        stopTimedLoop();
        setScreen("challengeThree");
        timerThree();
      }
      else{
        setScreen("failScreen");
      }
    }
  });
  // Checking answer for challenge three
  onEvent("challengeThree", "keydown", function(event) {
    if(event.key=="Enter"){
      var inputThree = getText("inputThree");
      if(inputThree=="The ability to touch type on touchscreen phones has been made possible with the use of specialized virtual keyboard software for touch typing."){
        stopTimedLoop();
        setScreen("challengeFour");
        timerFour();
      }
      else{
        setScreen("failScreen");
      }
    }
  });
  // Checking answer for challenge four
  onEvent("challengeFour", "keydown", function(event) {
    if(event.key=="Enter"){
      var inputFour = getText("inputFour");
      if(inputFour=="He found himself sitting at his computer, typing whatever came to mind. He was on a website entitled 10 fast fingers. This site tested how fast you were at typing."){
        stopTimedLoop();
        setScreen("challengeFive");
        timerFive();
      }
      else{
        setScreen("failScreen");
      }
    }
  });
  // Checking answer for challenge five
  onEvent("challengeFive", "keydown", function(event) {
    if(event.key=="Enter"){
      var inputFive = getText("inputFive");
      if(inputFive=="Frank Edward McGurrin, a court stenographer from Salt Lake City, Utah who taught typing classes, reportedly invented touch typing in 1888."){
        stopTimedLoop();
        setScreen("challengeSix");
        timerSix();
      }
      else{
        setScreen("failScreen");
      }
    }
  });
  // Checking answer for challenge six
  onEvent("challengeSix", "keydown", function(event) {
    if(event.key=="Enter"){
      var inputSix = getText("inputSix");
      if(inputSix=="The different areas of web design include web graphic design; interface design; authoring, including standardized code and proprietary software; user experience design; and search engine optimization."){
        stopTimedLoop();
        setScreen("challengeSeven");
        timerSeven();
      }
      else{
        setScreen("failScreen");
      }
    }
  });
  // Checking answer for challenge seven
  onEvent("challengeSeven", "keydown", function(event) {
    if(event.key=="Enter"){
      var inputSeven = getText("inputSeven");
      if(inputSeven=="Typing speed is important, but so is precision (typing faster is useless if accuracy is sacrificed. Improving typing skills requires focus on both, and it requires practice) a lot of practice. Develop muscle memory for typing certain types of commonly used letter parings."){
        stopTimedLoop();
        setScreen("challengeEight");
        timerEight();
      }
      else{
        setScreen("failScreen");
      }
    }
  });
  // Checking answer for challenge eight
  onEvent("challengeEight", "keydown", function(event) {
    if(event.key=="Enter"){
      var inputEight = getText("inputEight");
      if(inputEight=="If possible, try to consolidate all your loans. It has several benefits: (a) it oftentimes lowers the weight of your monthly payment burden and (b) it can oftentimes lengthen your payoff period. Consolidated loans may come with some disadvantages too. So, be sure to compare loan terms before you sign up."){
        stopTimedLoop();
        setScreen("winningScreen");
      }
      else{
        setScreen("failScreen");
      }
    }
  });
});
