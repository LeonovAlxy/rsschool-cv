# Aliasksei Leanovich
## Junior Frontend Developer
## Contact information:
* **Phone:** +375298064271
* **E-mail:** lleonovalxeyl@gmail.com
* **Telegram:** @alvaleonov
* **GitHub:** <https://github.com/LeonovAlxy>
## Briefly About Myself:
Frontend development has interested me since university. After graduating from the Faculty of International Relations of BSU, I began to pay attention to programming in the evenings. It has become a hobby for me, but I want it to become my main job. I think frontend development includes creativity, logical tasks, communication and self-development. That's why I like it. 
I believe that hard work, desire, and small steps every day will lead me to the goal of becoming a frontend developer.
## Skills and Proficiency:
* HTML5, CSS3
* JavaScript Basics
* Java Basics
* Git, GitHub
* VS Code, IntelliJ IDEA
## Code example:
* Task. Implement the function which takes an array containing the names of people that "like" an item.
```
function likes(names) {
      let countUser = names.length
    switch (countUser){
        case 0: return "no one likes this"
        break;
        case 1: return names[0]+' likes this'
        break;
        case 2: return names[0]+' and '+names[1]+' like this'
        break;
        case 3: return names[0]+', '+names[1]+' and '+names[2]+' like this'
        break
        default: let restofUsers =countUser-2
        return names[0]+', '+names[1]+' and '+ restofUsers+' others like this'
    }
return
}
```
* Task. Write a function *dirReduc* which will take an array of strings and returns an array of strings with the needless directions removed (W<->E or S<->N side by side).
```
function dirReduc(arr){
    const result = []
    for(let i = 0; i < arr.length; i++) {
        if(arr[i] === "NORTH" && arr[i + 1] === "SOUTH" || arr[i] === "SOUTH" && arr[i + 1] === "NORTH" || arr[i] === "EAST" && arr[i + 1] === "WEST" || arr[i] === "WEST" && arr[i + 1] === "EAST"){
            i++
        } else {
            if(result[result.length - 1] === "NORTH" && arr[i] === "SOUTH" || result[result.length - 1] === "SOUTH" && arr[i] === "NORTH" || result[result.length - 1] === "EAST" && arr[i] === "WEST" || result[result.length - 1] === "WEST" && arr[i] === "EAST"){
                result.pop()
            } else {
                result.push(arr[i])
            }
        }
    }
    return result
}
```
## Education:
**Belarusian State University**
*Faculty of International Relations* 
### Courses:
* RS Schools Course «JavaScript/Front-end. Stage 1» (in progress)
* Redev Course «Front-end» (in progress) <https://www.instagram.com/redev_courses/?hl=ru>
## Languages:
* English - Advanced (according to the online test at  www.efset.org)
<img src="file:///D:/images/EF_SET_Cert.png" />
* French -  Intermediate/Upper-intermediate
* Arabic - Pre-intermediate
* Polish - Basic
* Russian - Native
* Belarusian - Native

