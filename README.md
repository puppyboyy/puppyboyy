<center><img width="1587" height="2245" alt="dsdssgtdts" src="https://github.com/user-attachments/assets/5d35c231-53a4-443f-bb41-7059b3bad49e" /></center>
 <p align="center">
<img width="736" alt="tumblr_8b0e7cbec107ea178d646b226171a44a_e77f4720_1280" src="https://github.com/user-attachments/assets/74b828c1-ef4d-4721-b70c-7edee887945c" />
 </p>
<br>
<p align="center">
════════════════════════════════════════ <br>
 <br>
  ‿̩͙‿੭　∔⠀ৎ‿̩͙‿ 
 <br>
════════════════════════════════════════
</p>
<p align="center">
<img width="736" alt="tumblr_8b0e7cbec107ea178d646b226171a44a_e77f4720_1280" src="https://github.com/user-attachments/assets/74b828c1-ef4d-4721-b70c-7edee887945c" />
 </p>

 const str = '■'.repeat(48);

// Standard RGB gradient
const standardRGBGradient = gradient(['red', 'green']);

// Short HSV gradient: red -> yellow -> green
const shortHSVGradient = gradient(['red', 'green'], { interpolation: 'hsv' });

// Long HSV gradient: red -> magenta -> blue -> cyan -> green
const longHSVGradient = gradient(['red', 'green'], { interpolation: 'hsv', hsvSpin: 'long' });

console.log(standardRGBGradient(str));
console.log(shortHSVGradient(str));
console.log(longHSVGradient(str));
