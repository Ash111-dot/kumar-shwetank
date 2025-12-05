document.querySelectorAll("video").forEach(v => {
    v.currentTime = v.duration - 2;
})
