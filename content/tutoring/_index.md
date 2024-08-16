---
# title: "Tutor Resume"
# header: "Tutor Resume"
---

<div onclick="openFullscreenResume()" style="cursor: pointer;">
    {{< figure src="/tutoring/tutorcv2024.png" alt="tutoring resume" >}}
</div>

<script>
function openFullscreenResume() {
    // Select the image within the figure element
    var elem = document.querySelector('div img'); // This assumes this is the only image in the div or the first image inside the div
    if (elem.requestFullscreen) {
        elem.requestFullscreen();
    } else if (elem.webkitRequestFullscreen) { /* Safari */
        elem.webkitRequestFullscreen();
    } else if (elem.msRequestFullscreen) { /* IE11 */
        elem.msRequestFullscreen();
    }
}
</script>

<span class='caption'>▲ 教學與文字工作專用履歷</span>