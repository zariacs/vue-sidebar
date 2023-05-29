This was some practice making a responsive sidebar with Vue.js. Really done to practice before incorporating a similar sidebar into a larger project of mine.

Tools:
- <a href="https://vuejs.org/">Vue.js</a>
- <a href="https://sass-lang.com/">Sass</a>

Features:
- opens and closes smoothly
- indicates which page is the active page (makes use of vue class bindings and style bindings)
- settings button is separated from the rest of the menu using flex grow on a spacer div
- on larger screens, expanded sidebar pushes content over a bit
- on smaller screens, expanded sidebar covers content
- uses local storage to remember the user's last setting for expansion. ie, on page reload, remembers if the user last left the sidebar expanded or minimised for a better user experience

See photos below. Interact with this sidebar on <a href="https://vue-and-sass-sidebar.netlify.app/">Netlify</a>.

# Expanded
Apart from the Vue logo (#represent!!!), all icons and fonts used are from the Google Icons and Google Fonts selection.

![image](https://github.com/zariacs/vue-sidebar/assets/114250420/5d3a32ba-4199-436d-91be-2ea6d783f0eb)

# Shrunken
The sidebar minimizes on a single button click. Makes use of transitions for smooth animation. Interact with this sidebar on <a href="https://vue-and-sass-sidebar.netlify.app/">Netlify</a>.

![image](https://github.com/zariacs/vue-sidebar/assets/114250420/de8ea23d-0f4e-4166-8a32-28b3cb7d337e)

# Mobile
On mobile devices, the sidebar covers the content when expanded. This prevents the rest of the content from being awkwardly squished on smaller screens.

![image](https://github.com/zariacs/vue-sidebar/assets/114250420/868457ad-59ae-449e-aba6-0fa780e3024a)

![image](https://github.com/zariacs/vue-sidebar/assets/114250420/05a2269a-8ac0-4c38-a9da-dcaef32d2bfd)




-----

Note that on <a href="https://vue-and-sass-sidebar.netlify.app/">Netlify</a> only two routes are implemented because that's all that's needed to show the functionality. 

Thank you for looking! These are mostly notes for myself if I ever want to look back on this sidebar as a reference for my projects. If you're trying to recreate something like this and have any issues, feel free to reach out to me.
