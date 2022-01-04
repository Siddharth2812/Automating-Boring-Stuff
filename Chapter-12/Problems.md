### Practice Questions
1. Briefly describe the differences between the webbrowser, requests, bs4, and selenium modules.
>**webbrowser** : Comes with Python and opens a browser to a specific page.

>**requests** : Downloads files and web pages from the internet.

>**bs4** : Parses HTML, the format that web pages are written in.

>**selenium** : Launches and controls a web browser. The selenium module is able to fill in forms and simulate mouse clicks in this browser.

2. What type of object is returned by requests.get()? How can you access the downloaded content as a string value?
> requests.get() returns a `Response` type of object and it returns all the downloaded stuff as string to access it we call .text() function
3. What requests method checks that the download worked?
> raise_for_status()
4. How can you get the HTTP status code of a requests response?
> result.status_code()
5. How do you save a requests response to a file?
>file = open(url/file, 'wb')
>for chunk in res.iter_content(100000):
>    file.write(chunk)
6. What is the keyboard shortcut for opening a browser’s developer tools?
> F12
7. How can you view (in the developer tools) the HTML of a specific element on a web page?
> right-click the element and click on inspect
8. What is the CSS selector string that would find the element with an id attribute of main?
> #main
9. What is the CSS selector string that would find the elements with a CSS class of highlight?
> .highlight
10. What is the CSS selector string that would find all the <div> elements inside another <div> element?
> div div
11. What is the CSS selector string that would find the <button> element with a value attribute set to favorite?
> 'button[value = "favorite"]'
12. Say you have a Beautiful Soup Tag object stored in the variable spam for the element <div>Hello, world!</div>. How could you get a string 'Hello, world!' from the Tag object?
> var.getText()
13. How would you store all the attributes of a Beautiful Soup Tag object in a variable named linkElem?
> linkElem.attrs
14. Running import selenium doesn’t work. How do you properly import the selenium module?
> from selenium import webdriver
15. What’s the difference between the find_element_* and find_elements_* methods?
> find_element_* : it returns the first element that matches.
> find_elements_* : it returns all the maching elements.
16. What methods do Selenium’s WebElement objects have for simulating mouse clicks and keyboard keys?
> click() and sen_keys()
17. You could call send_keys(Keys.ENTER) on the Submit button’s WebElement object, but what is an easier way to submit a form with selenium?
> submit()
18. How can you simulate clicking a browser’s Forward, Back, and Refresh buttons with selenium?
> forward(), back(), refresh()