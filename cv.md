# Eugene Savitsky


** contacts **  *e-m@il*: eugenesavitsky89@gmail.com
 *vk.com*: <https://vk.com/vatanab3>
 *GitHub:* <https://github.com/EugeneSavitsky>


## About me:

I am a cheerful but responsible person.


After receiving higher education in the profession of "Highly Efficient Material Processing Processes".


I worked as an Engineer-Constructor. After a while, I began to work as a Foreman of a mechanical workshop,


but realized that working with people was not mine.


And I started to master programming on machine tools.


For 3 years now I have been working on machines, writing programs in G-Cods and in the Sinumerik shell.


Now I want to learn something new, that's why I started learning JS/FRONT-END.



## Skils:

* Quick self-study
* Communicability
* KOMPAS 3D
* Programming in the Sinumerik shell
* JavaScript (Basic)
* HTML/CSS (Basic)
* Git

## Code Example:

```
 function formatDuration (seconds) {

  if (seconds == 0) return "now";

  let second  = seconds % 60;
  let minutes = Math.floor(seconds / 60, 1);
  let hours   = Math.floor(seconds / 3600, 1);
  let days    = Math.floor(seconds / 86400, 1);
  let years   = Math.floor(seconds / 31104000, 1);
  
  let m = (minutes >= 60) ? minutes % 60 : minutes;
  let h = (hours >= 24) ? hours % 24 : hours;
  let d = (days >= 365) ? days % 365 : days;
 
  let stext = (second == 1) ? 'second' : 'seconds';
  let mtext = (m == 1) ? 'minute' : 'minutes';
  let htext = (h == 1) ? 'hour' : 'hours';
  let dtext = (d == 1) ? 'day' : 'days';
  let ytext = (years == 1) ? 'year' : 'years';
  
  let resultY = (years > 0) ? (`${years} ${ytext}, `) : '';
  let resultD = (d > 0) ? (`${d} ${dtext}, `) : '';
  let resultH = (h > 0) ? (`${h} ${htext}, `) : '';
  let resultM = (m > 0) ? (`${m} ${mtext}`) : '';
  let resultS = ((m+h+d+years) > 0) ? (` and ${second} ${stext}`) :(`${second} ${stext}`);
      resultS = (second == 0) ? '' : resultS;
      resultM = (second == 0 & m != 0 & h !=0) ? (` and ${m} ${mtext}`) : resultM;
      resultH = ((second == 0 || m == 0) & h!=0) ? (`${h} ${htext}`) : resultH;
      resultD = (second == 0 & h == 0 & m == 0) ? (`${d} ${dtext}`) : resultD;
  
  return (`${resultY}${resultD}${resultH}${resultM}${resultS}`);
}
```
## Experience:

* Codewars
* RS School (JS / FRONT-END Stage 0);

## Education:

* University: Vitebsk State Technological University, Highly Efficient Material Processing Processes.
* Courses: RS School (JS / FRONT-END Stage 0)

## Eanglish level: B1

* Studied at: Light Eanglish
* Practiced in Greece and Lithuania
