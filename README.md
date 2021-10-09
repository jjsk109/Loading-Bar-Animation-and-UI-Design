"# Loading-Bar-Animation-and-UI-Design" 

CSS Loading Bar Animation and UI Design | CSS Infinite Loading Progress Bar Animation Effects ,,

공부 링크 : https://www.youtube.com/watch?v=jP2GE-VIDLM ,,

학습한거 

animation: animate 6s ease-in-out infinite;

@keyframes animate{
    0%{
        width: 0;
        left: 0;
    }
    50%{
        width: 100%;
        left: 0;
    }
    100%{
        width: 0%;
        left: 100%;
    }
}

