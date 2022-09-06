# Dmitry Luferov #

## Junior Frontend Developer ##

---

## Contact information: ##

**Email:** luferov.dmitry@gmail.com

**Telegram:** @Luferov1

[**Instagram**](https://www.instagram.com/luferov1/?hl=ru)

---

## About myself: ##
My name is Dmitry. I am 20 years old. I live in Minsk, Belarus. I am studying at the BSUIR as an engineer in radio engineering. 

When I turned 20, I decided to change my speciality. I chose to study Software engineering because I think it’s very prestigious and modern job. I am an ambitious person and this job suits me. Working in a team isn’t a problem for me because I have enough communicative and leadership skills. My hobby is playing football, so I know what a team is and how important is it to help each other and to make collective decisions. I am cheerful and open-minded person, so that’s another reason why I can easily join any team.

I met programming at school. Also, I had 2 semesters of programming at university. I took a small part mobile application development in 2021. Now I am studying in RS School.

I consider that I have enough personal and work skills and to get this job. 

---

## Skills and Proficiency: ##

* HTML5
* CSS3
* JavaScript basics
* Git, GitHub
* Microsoft office Word
* Adobe Photoshop (interimidiate)

---

## Code example: ##

**Human readable duration format**
 
_Your task in order to complete this Kata is to write a function which formats a duration, given as a number of seconds, in a human-friendly way.
The function must accept a non-negative integer. If it is zero, it just returns "now". Otherwise, the duration is expressed as a combination of years, days, hours, minutes and seconds._

    function formatDuration (seconds) {

      if (seconds == 0) return 'now';
      let second = 0, minute = 0, hour = 0, day = 0, year = 0;
      let result = seconds;
      let str = '';

      for (; result >= 31536000; year++) {
        result -= 31536000;
      }
      for (; result >= 86400; day++) {
        result -= 86400;
      }
      for (; result >= 3600; hour++) {
        result -= 3600;
      }
      for (; result >= 60; minute++) {
        result -= 60;
      }
      second = result;
   
      year = `${year} year`;
      day = `${day} day`;
      hour = `${hour} hour`;
      minute = `${minute} minute`
      second = `${second} second`;
      let arr = [year, day, hour, minute, second];

      for (let i = 0; i < arr.length; i++) {

        if ( arr[i].startsWith('0') ) {
          arr.splice(i, 1);
          i--;
        }
      } 
      for (let i = 0; i < arr.length; i++) {

        if ( !arr[i].startsWith('1 ') ) arr[i] += 's';
      }

      if (arr.length == 1) {
        str = arr[0];

      } else if (arr.length == 2) {
        str = `${arr[0]} and ${arr[1]}` }

      else {
        for (let i = 0; i < arr.length - 2; i++ ) {
        str += `${arr[i]}, `;
      }

      str += `${arr[arr.length -2]} and ${arr[arr.length - 1]}`
      }
      return str;
    }

 ---

 ## Courses: ## 

 * HTML and CSS tutorials [schoolsw3](https://schoolsw3.com/html/) (completed)
 * JavaScript manual on [learnjavascript.ru](https://learn.javascript.ru/) 
 * [**Mimo**](https://getmimo.com/): Web Development (80%)
 * [**Codewars**](https://www.codewars.com) rank: **5 kuy**
 * **RS School** Course «JavaScript/Front-end. Stage 0» (187 place, 904.6/930 total points)

---

## Languages: ##

* **English** - Intermediate/Upper-intermediate
* **Russian** - Native
* **Belarussian** - Intermediate