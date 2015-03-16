After creating a drupal installation with the drupal-factory, do:


docker run -it --rm --name $CONTAINER_NAME -v $DESIRED_INPUT_DIR/drupal:/var/www/html -P raphabot/drupal-server


Example:

docker run -it --rm --name drupal-server -v /home/nice_user/drupal/output/drupal:/var/www/html -p 80:80 raphabot/drupal-server
