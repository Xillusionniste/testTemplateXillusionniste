/*********************/
/*  Left Bar Closed  */
/*                   */
/*********************/

AdminLTE.min.css:7

@media (min-width: 768px)
.sidebar-mini.sidebar-collapse .main-sidebar {
    -webkit-transform: translate(0, 0);
    -ms-transform: translate(0, 0);
    -o-transform: translate(0, 0);
    transform: translate(0, 0);
    width: 50px!important;
    z-index: 850;
}



/*********************/
/*  Left Bar Opened  */
/*                   */
/*********************/

AdminLTE.min.css:7

.main-sidebar, .left-side {
    position: absolute;
    top: 0;
    left: 0;
    padding-top: 50px;
    min-height: 100%;
    width: 230px;
    z-index: 810;
    -webkit-transition: -webkit-transform .3s ease-in-out,width .3s ease-in-out;
    -moz-transition: -moz-transform .3s ease-in-out,width .3s ease-in-out;
    -o-transition: -o-transform .3s ease-in-out,width .3s ease-in-out;
    transition: transform .3s ease-in-out,width .3s ease-in-out;
}