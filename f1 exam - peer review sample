let input = 0
let answer = 0

while (true) {
  input = prompt('Guess number')
  answer = parseInt(input, 10)
  if (!isNaN(answer) && answer <= 100 && answer > 0) {
    console.log(`Answer is: ${answer}`)
    break
  }
}

let count = 0
while (count < 100) { // to avoid infinite loop
  let comAnswer = Math.floor(Math.random() * 100)
  console.log(`#${count + 1}: Computer guess: ${comAnswer}, ${checkAnswer(comAnswer)}`)
  count++
}

function checkAnswer (guess) {
  if (guess === answer) {
    return 'Win!'
  } else if (guess > answer) {
    return 'too bigger!'
  } else {
    return 'too small!'
  }
}
