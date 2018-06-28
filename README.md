# Service Builder Recipe
Example recipe for SAREhub Service Builder.

## How to use it?
Install SAREhub Service Builder composer plugin and use **inject** command inside terminal

### Example usage:

``` 
    composer inject github SAREhub/service-builder-recipe Project/Namespace
```

This command should extract source files to _src/Project/Namespace_ directory in your working dir.

Additional files from recipe will be extracted in directories where have been placed before. In this case 
this will be _bin/init.sh_ folder in your working dir.
