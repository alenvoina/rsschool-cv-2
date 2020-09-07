# Junior Developer Resume

## Alexandr Mikholap
email: alxandr.mikholap@gmail.com

## Goals

My goals are to learn js and web developing. I want to work in it-organization and it is the reason why i tried to learn more.

## Skills

1. C# and .Net
 1. ASP.NET Core
 2. EntityFramework and EntityFramework Core
2. JS
3. HTML/CSS/Less

## Code Examples

```javascript 

document.querySelector("#btn-input").addEventListener("click", (e) => {
    e.preventDefault();

    const messageInput = document.querySelector("#text-input").value;
    const userName = document.querySelector("#name-input").value;
    if (messageInput != "") {
        const data = new FormData();
        data.append("name", userName);
        data.append("message", messageInput);
        
        document.querySelector("#text-input").value = '';
        fetch("home/SendMessage", {
            method: "POST",
            body: data
        }).catch(error => console.error("Error", error));
    }
});

```
## Experience

I have experience in page layout and experience in creating course project.

## Education

1. Course of C#;
2. Offline learning(YouTube, books and website);
3. College.

## English

My english level is A2.
