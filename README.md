﻿<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="utf-8" />
    <title>Welcome to ASP.NET 5</title>
    <style>
        html {
            background: #f1f1f1;
            height: 100%;
        }

        body {
            background: #fff;
            color: #505050;
            font: 14px 'Segoe UI', tahoma, arial, helvetica, sans-serif;
            margin: 1%;
            min-height: 95.5%;
            border: 1px solid silver;
            position: relative;
        }

        #header {
            padding: 0;
        }

            #header h1 {
                font-size: 44px;
                font-weight: normal;
                margin: 0;
                padding: 10px 30px 10px 30px;
            }

            #header span {
                margin: 0;
                padding: 0 30px;
                display: block;
            }

            #header p {
                font-size: 20px;
                color: #fff;
                background: #007acc;
                padding: 0 30px;
                line-height: 50px;
                margin-top: 25px;

            }

                #header p a {
                    color: #fff;
                    text-decoration: underline;
                    font-weight: bold;
                    padding-right: 35px;
                    background: no-repeat right bottom url(data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABcAAAAWCAMAAAAcqPc3AAAANlBMVEUAAAAAeswfitI9mthXp91us+KCvuaTx+mjz+2x1u+83PLH4vTR5/ba7Pjj8Pns9fv1+v3////wy3dWAAAAAXRSTlMAQObYZgAAAHxJREFUeNp9kVcSwCAIRMHUYoH7XzaxOxJ9P8oyQ1uIqNPwh3s2aLmIM2YtqrLcQIeQEylhuCeUOlhgve5yoBCfWmlnlgkN4H8ykbpaE7gR03AbUHiwoOxUH9Xp+ubd41p1HF3mBPrfC87BHeTdaB3ceeKL9HGpcvX9zu6+DdMWT9KQPvYAAAAASUVORK5CYII=);
                }

        #main {
            padding: 5px 30px;
            clear: both;
        }

        .section {
            width: 21.7%;
            float: left;
            margin: 0 0 0 4%;
        }

            .section h2 {
                font-size: 13px;
                text-transform: uppercase;
                margin: 0;
                border-bottom: 1px solid silver;
                padding-bottom: 12px;
                margin-bottom: 8px;
            }

            .section.first {
                margin-left: 0;
            }

                .section.first h2 {
                    font-size: 24px;
                    text-transform: none;
                    margin-bottom: 25px;
                    border: none;
                }

                .section.first li {
                    border-top: 1px solid silver;
                    padding: 8px 0;
                }

            .section.last {
                margin-right: 0;
            }

        ul {
            list-style: none;
            padding: 0;
            margin: 0;
            line-height: 20px;
        }

        li {
            padding: 4px 0;
        }

        a {
            color: #267cb2;
            text-decoration: none;
        }

            a:hover {
                text-decoration: underline;
            }

        #footer {
            clear: both;
            padding-top: 50px;
        }

            #footer p {
                position: absolute;
                bottom: 10px;
            }
    </style>
</head>
<body>

    <div id="header">
        <h1>Welcome to ASP.NET 5 Preview</h1>
        <span>
            We've made some big updates in this release, so it’s <b>important</b> that you spend 
            a few minutes to learn what’s new.
            <br /><br />
            ASP.NET 5 has been rearchitected to make it <b>lean</b> and <b>composable</b>. It's fully 
            <b>open source</b> and available on <a href="http://go.microsoft.com/fwlink/?LinkID=517854">GitHub</a>.
            <br />
            Your new project automatically takes advantage of modern client-side utilities 
            like <a href="http://go.microsoft.com/fwlink/?LinkId=518004">Bower</a> and <a href="http://go.microsoft.com/fwlink/?LinkId=518005">npm</a>
            (to add client-side libraries) and <a href="http://go.microsoft.com/fwlink/?LinkId=518006">Grunt</a> and 
            <a href="http://go.microsoft.com/fwlink/?LinkId=518007">Gulp</a> (for client-side build and automation tasks).

            <br /><br />
            We hope you enjoy the new capabilities in ASP.NET 5 and Visual Studio 2015.
            <br />
            The ASP.NET Team
        </span>
        <p>You've created a new ASP.NET 5 project. <a href="http://go.microsoft.com/fwlink/?LinkId=518016">Learn what's new</a></p>
    </div>

    <div id="main">
        <div class="section first">
            <h2>This application consists of:</h2>
            <ul>
                <li>Sample pages using ASP.NET MVC 6</li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkId=518006">Grunt</a> and <a href="http://go.microsoft.com/fwlink/?LinkId=518004">Bower</a> for managing client-side resources</li>
                <li>Theming using <a href="http://go.microsoft.com/fwlink/?LinkID=398939">Bootstrap</a></li>
            </ul>
        </div>

        <div class="section">
            <h2>New concepts</h2>
            <ul>
                <li><a href="http://go.microsoft.com/fwlink/?LinkId=518008">The 'wwwroot' explained</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkId=518012">Configuration in ASP.NET 5</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkId=518013">Dependency Injection</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkId=518014">Razor TagHelpers</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=517849">Manage client tasks using Grunt</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=517850">Develop on different platforms</a></li>
            </ul>
        </div>

        <div class="section">
            <h2>Customize app</h2>
            <ul>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=398600">Add Controllers and Views</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=398602">Add Data using EntityFramework</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=398603">Add Authentication using Identity</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=398606">Add real time support using SignalR</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=398604">Add Class library</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkId=518009">Add Web APIs with MVC 6</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=517848">Add client packages using Bower</a></li>
            </ul>
        </div>

        <div class="section last">
            <h2>Deploy</h2>
            <ul>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=517851">Run your app locally</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=517852">Run your app on ASP.NET Core 5</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=517853">Run commands in your project.json</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkID=398609">Publish to Microsoft Azure Web Sites</a></li>
                <li><a href="http://go.microsoft.com/fwlink/?LinkId=518019">Publish to the file system</a></li>
            </ul>
        </div>

        <div id="footer">
            <p>We would love to hear your <a href="http://go.microsoft.com/fwlink/?LinkId=518015">feedback</a></p>
        </div>
    </div>

</body>
</html>