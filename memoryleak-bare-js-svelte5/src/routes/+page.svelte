<h1>Memory leak test</h1>

<span style="font-style: italic">Preconditions: Make sure you've run `npm run build` and `npm run preview` for testing this.</span>
<span style="font-style: italic">You should probably run an isolated browser instance to avoid additional heap size due to the behavior of some extensions.</span>
<ol>
    <li>Open up Memory Tab in DevTools (Ctrl + Shift + i)</li>
    <li>Go to <a href="/sub">sub page</a> to enhance memory footprint and return back to the current home page</li>
    <li>Collect garbage (click button and wait ~10s)</li>
    <li>Make a heap snapshot and look at the heap size</li>
    <li>Repeat steps 2 - 4 multiple times</li>
</ol>
