(function () {
    var marioVideo = document.getElementById("video1"),
        videoFullscreen = document.getElementById("video-fullscreen");

    if (marioVideo && videoFullscreen) {
        videoFullscreen.addEventListener("click", function (evt) {
            if (marioVideo.requestFullscreen) {
                marioVideo.requestFullscreen();
            }
            else if (marioVideo.msRequestFullscreen) {
                marioVideo.msRequestFullscreen();
            }
            else if (marioVideo.mozRequestFullScreen) {
                marioVideo.mozRequestFullScreen();
            }
            else if (marioVideo.webkitRequestFullScreen) {
                marioVideo.webkitRequestFullScreen();
            }
        }, false);
    }
    var cancelFullScreen = document.getElementById("cancel-fullscreen");
    if (cancelFullScreen) {
        cancelFullScreen.addEventListener("click", function () {
            if (document.exitFullscreen) {
                document.exitFullscreen();
            }
            else if (document.msExitFullscreen) {
                document.msExitFullscreen();
            }
            else if (document.mozCancelFullScreen) {
                document.mozCancelFullScreen();
            }
            else if (document.webkitCancelFullScreen) {
                document.webkitCancelFullScreen();
            }
        }, false);
    }

})();
