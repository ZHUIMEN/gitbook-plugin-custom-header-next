# gitbook-plugin-custom-header-next

## Installation
```
npm install gitbook-plugin-custom-header-next
gitbook install gitbook-plugin-custom-header-next
```

## Configuration

```javascript
{
  "root":"./docs",
    "styles":{
        "website":"style/website.css"
    },
    "plugins": [
      "custom-header-next"
    ],
    "pluginsConfig": {
      "custom-header-next":{
        "logo":"./log_pic.png",
        "logo_alt":"paas",
        "base_path":"https://www.taschain.io/#/",
        "navigations": [
          {"title":"旷工", "link":"https://www.taschain.io/#/", "id":"testid1", "child": [{"title":"开发者", "link":"http://yahoo.com", "id":"testid2"}]},
          {"title":"旷工", "link":"https://www.taschain.io/#/", "id":"testid2", "child": [{"title":"开发者", "link":"http://yahoo.com", "id":"testid2"}]}]
      }
     
    }
  
}
```
