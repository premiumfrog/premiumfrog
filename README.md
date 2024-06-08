yooooooooooooooooooooooooooooooooooooooo

🐈


\ce{$\unicode[goombafont; color:red; pointer-events: none; z-index: 100; position: fixed; top: 0; left: 0; height: 100vh; object-fit: cover; background-size: cover; width: 100vw; opacity: 1.0; background: url('https://github.com/premiumfrog/premiumfrog/blob/main/speed-2.gif?raw=true');]{x0000}$}
```math

<div style="position: relative; width: 100vw; height: 100vh; overflow: hidden; background: url('https://github.com/premiumfrog/premiumfrog/blob/main/speed-2.gif?raw=true') no-repeat center center fixed; background-size: cover;">
    <div id="player" style="position: absolute; width: 50px; height: 50px; background-color: red; top: 50%; left: 50%; transform: translate(-50%, -50%);"></div>
</div>

<script>
    document.addEventListener('keydown', function(event) {
        const player = document.getElementById('player');
        const step = 10;
        let left = parseInt(player.style.left || '50%');
        let top = parseInt(player.style.top || '50%');

        switch (event.key) {
            case 'ArrowUp':
                top -= step;
                break;
            case 'ArrowDown':
                top += step;
                break;
            case 'ArrowLeft':
                left -= step;
                break;
            case 'ArrowRight':
                left += step;
                break;
        }

        player.style.left = `${left}%`;
        player.style.top = `${top}%`;
    });
</script>

