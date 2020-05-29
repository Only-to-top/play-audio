# play-audio

```js
document.addEventListener('DOMContentLoaded', () => {

    const audio = document.getElementById('audio');
    const play_btn = document.getElementById('play_btn');

    play_btn.addEventListener('click', () => {
        play_btn.classList.toggle('play');

        if (play_btn.getAttribute('class') == 'play-btn play') {
            audio.play();
        } else {
            audio.pause();
        }
    });
    
});
```
