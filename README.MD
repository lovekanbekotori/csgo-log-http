# CSGO LOG HTTP

## Author
Shugo Kawamura  
Github : [**FlowingSPDG**](http://github.com/FlowingSPDG)  
Twitter : [**@FlowingSPDG**](http://twitter.com/FlowingSPDG) / [**@FlowingSPDG_EN**](http://twitter.com/FlowingSPDG_EN)

## About
This is HTTP Log parser middleware for Gin.
Parses log line from CSGO Server,and allows you to do something by those datas.

## Usage(Example)
- Go to examples folder,and ``go run main.go`` .
- Enable logs by CSGO Server side. ``logaddress_add_http "http://YOUR-GIN-Server:3090"; log on;``
- You'll get std log output which describes informations in log line.