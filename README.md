Elastic Beanstalk URL
http://imagefilter-service-dev.us-east-1.elasticbeanstalk.com/

Elastic Beanstalk URL for format for filtering an online image. You just append the image url to it
http://imagefilter-service-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=

This service doesn't work for the image url provided in the project rubrics
https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg

However, it works well with other image urls such as the one below from pexels.com
https://images.pexels.com/photos/1181474/pexels-photo-1181474.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1

Concatenating the Elastic Beanstalk URL and the image url above, the total url to be run by the browser becomes
http://imagefilter-service-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://images.pexels.com/photos/1181474/pexels-photo-1181474.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1