Run a container with a mounted host file.

* docker run -v \<full host path>:\<path in container to copy to> \<container tag name>
* example:
* docker run -v C:/some/test/folder:/some/app/folder test-tag-name

Copy from a container (running or not) to a host folder

* docker cp \<container name>:\<full host path>
* example:
* docker cp some_name:/app/folder C:/some/host/folder