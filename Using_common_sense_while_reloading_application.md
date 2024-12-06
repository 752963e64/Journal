# Do not restart your service like dumbasses...

"Something slipped into our application while it was reloading..."

## Know your processing.

You must close entry while reloading your application... Initialisation may be partial...

And this can lead to real problem for your entire application.

networked application using privileged port are root.

local application loading huge files, needs to be statefull. Way more with threads concurrency.

###### 75293e64@tutanota.com

