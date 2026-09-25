# NEXOR<!DOCTYPE html>
<html lang="bg">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="theme-color" content="#080808">
<title>NEXOR</title>

<style>
* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}

body {
    background: #080808;
    color: #fff;
    font-family: Arial, sans-serif;
    height: 100vh;
    overflow: hidden;
}

.app {
    height: 100vh;
    display: flex;
    flex-direction: column;
}

.header {
    height: 65px;
    display: flex;
    align-items: center;
    padding: 0 18px;
    border-bottom: 1px solid #222;
    background: #0d0d0d;
}

.logo {
    font-size: 25px;
    font-weight: bold;
    letter-spacing: 4px;
}

.status {
    margin-left: auto;
    font-size: 12px;
    color: #777;
}

.chat {
    flex: 1;
    overflow-y: auto;
    padding: 20px 15px 110px;
}

.message {
    max-width: 88%;
    padding: 13px 15px;
    margin-bottom: 13px;
    border-radius: 17px;
    line-height: 1.45;
    font-size: 15px;
    white-space: pre-wrap;
}

.nexor {
    background: #171717;
    border: 1px solid #252525;
    margin-right: auto;
}

.user {
    background: #fff;
    color: #000;
    margin-left: auto;
}

.input-area {
    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
    padding: 
