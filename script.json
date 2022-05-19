function omeSpam()
{
    var wlc = ['Hi', 'Hey', 'Sup', 'Hello', 'Hi lol', ':P', 'Whats up', 'Yo', 'Heyy']; //just to bypass detection
    var Ad = ['INSERT YOUR STRING HERE', 'INSERT YOUR STRING HERE', 'INSERT YOUR STRING HERE']; //more srings = less chance you will get captcha
    let sendButton = document.querySelector('.sendbtn')
    var rwlc = wlc[Math.floor(Math.random()*wlc.length)];
    var rAd = Ad[Math.floor(Math.random()*Ad.length)];
    document.querySelector('.chatmsg').value = rwlc ;
    sendButton.click()
    document.querySelector('.chatmsg').value = rAd ;
    sendButton.click()
    setTimeout(() => {document.querySelector('.disconnectbtn').click();},5000)
    setTimeout(() => {document.querySelector('.disconnectbtn').click();},5000)
}
//run in console
//use for text if you dont wanna get banned quick
setInterval(omeSpam,7000)
