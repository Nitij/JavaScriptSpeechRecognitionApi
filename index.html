<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    
    <button id='btnGiveCommand'>Give Command!</button>
    <br><br>
    <span id='message'></span>
    <br><br>
    
    <input id='chkSteve' type="checkbox"> Steve Rogers
    <br>
    <input id='chkTony' type="checkbox"> Tony Stark
    <br>
    <input id='chkBruce' type="checkbox"> Bruce Banner
    <br>
    <input id='chkNick' type="checkbox"> Nick Fury
    
    <script>
        var message = document.querySelector('#message');

        var SpeechRecognition = SpeechRecognition || webkitSpeechRecognition;
        var SpeechGrammarList = SpeechGrammarList || webkitSpeechGrammarList;

        var grammar = '#JSGF V1.0;'

        var recognition = new SpeechRecognition();
        var speechRecognitionList = new SpeechGrammarList();
        speechRecognitionList.addFromString(grammar, 1);
        recognition.grammars = speechRecognitionList;
        recognition.lang = 'en-US';
        recognition.interimResults = false;

        recognition.onresult = function(event) {
            var last = event.results.length - 1;
            var command = event.results[last][0].transcript;
            message.textContent = 'Voice Input: ' + command + '.';

            if(command.toLowerCase() === 'select steve'){
                document.querySelector('#chkSteve').checked = true;
            }
            else if (command.toLowerCase() === 'select tony'){
                document.querySelector('#chkTony').checked = true;
            }
            else if (command.toLowerCase() === 'select bruce'){
                document.querySelector('#chkBruce').checked = true;
            }
            else if (command.toLowerCase() === 'select nick'){
                document.querySelector('#chkNick').checked = true;
            }   
        };

        recognition.onspeechend = function() {
            recognition.stop();
        };

        recognition.onerror = function(event) {
            message.textContent = 'Error occurred in recognition: ' + event.error;
        }        

        document.querySelector('#btnGiveCommand').addEventListener('click', function(){
            recognition.start();

        });


    </script>
</body>
</html>