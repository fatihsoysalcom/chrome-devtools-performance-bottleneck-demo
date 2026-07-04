# Chrome DevTools Performance Bottleneck Demo

This example demonstrates common web performance bottlenecks, specifically long-running JavaScript tasks that block the main thread and excessive DOM manipulation. Users can observe UI unresponsiveness and analyze these issues using Chrome DevTools' Performance tab, identifying blocked main thread activity, layout, and paint events.

## Language

`html`

## How to Run

1. Save the code as `index.html`.
2. Open `index.html` in your Chrome browser.
3. Open Chrome DevTools (F12 or Ctrl+Shift+I), go to the "Performance" tab.
4. Click the "Start Heavy Operation" button. While it's running, try clicking the "Try to click me" button multiple times to feel the unresponsiveness. Then, stop recording in DevTools to analyze the performance profile.

## Original Article

This example accompanies the Turkish article: [Chrome DevTools ile Performans Darboğazlarını Bulma](https://fatihsoysal.com/blog/?p=43049).

## License

MIT — see [LICENSE](LICENSE).
