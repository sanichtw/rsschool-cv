# **Nikita Kozlov**

## **Contacts**
**Phone**: +375297462546  
**E-mail:** sanichtw@gmail.com  
**Telegram:** @sanfrancisco185  
[LinkedIn](https://www.linkedin.com/in/sanfrancisco185/)  

## **About Me**  
I Work as an Engineer in the Field of Relay Protection. I Started Frontend Development at the End of 2020.  
I Have Experience in Creating Data Filtering Components, Login Forms. My Goal is to Become a Confident Developer and Improve Myself.  

## **Skills**
* JavaScript
* HTML
* CSS
* React

## **Code examples**  
Given a String of Words, Return the Length of The Shortest Word
```
function findShort(s) {
    let arr = s.split(' ')
    let minLengthItem = arr[0];

    arr.forEach(el => {
        if (el.length < minLengthItem.length) {
            minLengthItem = el
        }
    })

    return minLengthItem
}
```
