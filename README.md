# Portfolio-Website
This is my portfolio website, I use it to post projects and other things.
## Design
- This website mainly uses flexbox
## Problems I ran into
- Because I set the content in my project section to wrap, when resizing it lead footer to be pushed up.
**Solution**: I set `flex-grow: 1` to .content and .bio, allowing them to grow to the available space and gave .project a min height