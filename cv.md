## *Iolanta Averyanova*  
### Junior Frontend Developer  
### Contact information:
 - phone: +375298109242
 - email: iolantazhiznevskaya@gmail.com
 - [linkedin](www.linkedin.com/in/iaveryanova)
 - [github](https://github.com/iaveryanova)
 - [telegram](https://t.me/iaveryanova)

### Briefly About Myself:
My background is chemistry. I graduated Belarussian State University. I worked for a pharmaceutical company. I was a Regulatory Affairs Manager. My role was related to preparing different documents for quality control of medicines. And I am grateful for the experience and knowledge that I have gained. But I have long been interested in the topic of software development. For myself, I chose Front-end development. Because I like to immediately see the result of my work. 
I have experience in development of web pages using HTML, CSS/SCSS (cross-browser adaptive and semantic layout). I have learned JavaScript while developing the client side of a web application. I have implemented applications on React and Angular using JavaScript/TypeScript.
Seeking a full-time position  in a company with a modern approach to development and a collaborative team. Planning to improve my skills in front-end deeper.

### Skills and Proficiency:
-   HTML & CSS/SCSS
-   JavaScript
-   TypeScript
-   React
-   Node.js/Express
-   Sequelize/MySQL
-   Angular (basics)
-   Material UI/Bootstrap/Mantine
-   GitHub/GIT
-   Figma/Photoshop

### Code example:
*Peak array index KATA from CODEWARS: Given an array of ints, return the index such that the sum of the elements to the right of that index equals the sum of the elements to the left of that index. If there is no such index, return -1. If there is more than one such index, return the left-most index.*

```
function peak(arr) {

  for (let i = 1; i < arr.length - 1; i++) {
    let leftSum = arr.slice(0, i).reduce((accumulator, currentValue) => accumulator + currentValue);
    let rightSum = arr.slice(i + 1).reduce((accumulator, currentValue) => accumulator + currentValue);
    if (leftSum === rightSum) {
      return i;
    }
  }
  return -1;
}
```

### Experience:  
*January 2023 - March 2023*  
 **Itransition company**  
Trainee front-end developer  
Carrying out tasks involved in full-stack web development.  
Technology stack: React, TypeScript/JavaScript, Node.js/Express, MySQL, Sequelize.  

**My study projects**
-   Application for searching and managing vacancies on React/JavaScript. API service Superjob was used ([https://api.superjob.ru/](https://api.superjob.ru/)).
Github: [https://github.com/iaveryanova/jobSearchApp](https://github.com/iaveryanova/jobSearchApp)  
Deploy: https://job-search-8803r2wjy-iaveryanova.vercel.app/

-   Weather app on Angular/TypeScript is the little web app for getting current and forecast daily weather on five days by city name. It was created by using [https://openweathermap.org/](https://openweathermap.org/). HttpClientModule, FormsModule, Angular Material UI are used.  
Github: [https://github.com/iaveryanova/openWeatherAngular](https://github.com/iaveryanova/openWeatherAngular)  
Deploy: [https://iaveryanova.github.io/openWeatherAngular/](https://iaveryanova.github.io/openWeatherAngular/)

-   FilmSearch app on Angular/TypeScript queries the OMDb API in order to retrieve information about requested movies. Using HttpClientModule, MatPaginatorModule, FormsModule.  
Github: [https://github.com/iaveryanova/filmSearchAngular](https://github.com/iaveryanova/filmSearchAngular)  
Deploy: [https://iaveryanova.github.io/filmSearchAngular/](https://iaveryanova.github.io/filmSearchAngular/)

-   UserList app on React/TypeScript. An example CRUD application using React, Redux, React Hooks, API request with axios.  
Github: [https://github.com/iaveryanova/userListReact](https://github.com/iaveryanova/userListReact)  
Deploy: [https://iaveryanova.github.io/userListReact/](https://iaveryanova.github.io/userListReact/)

### Education:
**Belarusian State University  (2013 - 2017)**  
*Faculty of Chemistry*  
Pharmaceutical chemist  
#### Courses:  
**IT Step Academy (2021 - 2022)**  
*Front-end developer*  

### Languages:
- Russian - Native
- English - Intermediate
