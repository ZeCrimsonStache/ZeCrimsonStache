<body id="body">

    <input id="input">
    <button id="button">Submit</button>
   
    <script>document.getElementById('button').onclick = function(){
    let submit = document.getElementById('input').value;
    let paragraph = document.createElement('p');
    paragraph.textContent = `I created this element. Also you wrote ${submit} in the textbox.`;
    const body = document.getElementById('body');
    body.appendChild(paragraph);
}</script>
</body>
