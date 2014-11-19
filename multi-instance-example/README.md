This is a simple [camunda](http://www.camunda.org) process application, that demonstrates a process containing a multi instance user task. If you have the requirement to have boundary events that quit all instances, you need a surrounding transaction. Therefore, this example would not work:

![Screenshot](src/main/resources/multi-instance-task.png?raw=true "Screenshot")