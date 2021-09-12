<template>
    <div class="Header">
        <style>
            .Header{
                position: fixed;
                z-index: 2;
                background: black;
                width:100%;
                height: 70px;
                margin-top: -22px;
                margin-left: -10px;
            }
            /* By Dominik Biedebach @domobch */

            section {
            height: 100vh;
            }

            /* NAVIGATION */
            nav {
            position:relative;
            width: 100vw;
            background: #000000;
            top:-5px;
            }

            /* By Dominik Biedebach @domobch */
            nav ul {
            list-style: none;
            text-align: center;
            }
            nav ul li {
            display: inline-block;
            }
            nav ul li a {
            display: block;
            padding: 15px;
            text-decoration: none;
            color: #aaa;
            font-weight: 800;
            text-transform: uppercase;
            margin: 0 10px;
            }
            nav ul li a,
            nav ul li a:after,
            nav ul li a:before {
            transition: all .5s;
            }

            /* By Dominik Biedebach @domobch */


            /* stroke */
            nav.stroke ul li a,
            nav.fill ul li a {
            position: relative;
            }
            nav.stroke ul li a:after,
            nav.fill ul li a:after {
            position: absolute;
            bottom: 0;
            left: 0;
            right: 0;
            margin: auto;
            width: 0%;
            content: '.';
            color: transparent;
            background: #333;
            height: 1px;
            }
            nav.stroke ul li a:hover:after {
            width: 100%;
            }

            nav.fill ul li a {
            transition: all 2s;
            }
            /* By Dominik Biedebach @domobch */

            nav.fill ul li a:after {
            text-align: left;
            content: '.';
            margin: 0;
            opacity: 0;
            }
            nav.fill ul li a:hover {
            color: #330003;
            z-index: 1;
            }
            nav.fill ul li a:hover:after {
            z-index: -10;
            animation: fill 1s forwards;
            -webkit-animation: fill 1s forwards;
            -moz-animation: fill 1s forwards;
            opacity: 1;
            }
            #HeaderMyName{
                position:absolute;
                color: white;
                top:-6px;
                left:10px;
            }



            /* Keyframes */
            @-webkit-keyframes fill {
            0% {
                width: 0%;
                height: 1px;
            }
            50% {
                width: 100%;
                height: 1px;
            }
            100% {
                width: 100%;
                height: 100%;
                background: #990008;
            }
            }
        </style>
        <link href='https://fonts.googleapis.com/css?family=Roboto:500,900,100,300,700,400' rel='stylesheet' type='text/css'>
        <nav class="fill">
            <h1 id="HeaderMyName">SOTA OKUDA</h1>
            <ul>
                <li><a href="">TOP</a></li>
                <li><a href="#IntroductionSection">About</a></li>
                <li><a href="#EngineeringSection">Engineering</a></li>
                <li><a href="#SocialSection">Social Contribtion</a></li>
                <li><a href="#ResearchSection">Research</a></li>
            </ul>
        </nav>

    </div>
</template>