# Happy Birthday!
Open the HTML file in your browser or paste this in your browser's address bar :)  
```
data:text/html,<script>let audioContext = new AudioContext();let i = 0;([[0, 0.7], [0, 0.3], [2], [0], [5], [4, 2],[0, 0.7], [0, 0.3], [2], [0], [7], [5, 2],[0, 0.7], [0, 0.3], [12], [9], [5], [4], [2, 2],[10, 0.7], [10, 0.3], [9], [5], [7], [5, 2]]).map(([n, dur = 1]) => {let oscillator = audioContext.createOscillator();oscillator.start(i);oscillator.frequency.value *= Math.pow(1.06, n);h = audioContext.createGain();i += dur / 1.5;h.gain.linearRampToValueAtTime(0, i);oscillator.connect(h);h.connect(audioContext.destination)});</script>
```
