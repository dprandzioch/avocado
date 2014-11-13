### Avocado
Avocado is a deployment framework for web applications written in Ruby.

The current release is 0.4.1.

### Licensing
Avocado is licensed under the GPLv2. For more Information have a look into the LICENSE file.

### Limitations
Avocado does currently only work if you use Git for as version control system and SSH to deploy. Furthermore, the only implemented authentication method for both SSH and Git is public key authentication.

### Getting started
Be sure that you have installed Ruby 2.0 or higher and RubyGems. Then the Installation is as easy as

```
$ gem install avodeploy
```

After the installation completed successfully, you can run the `avo` command to access the Avocado command line utility.

### Use Avocado in your project
In your project folder just run

```
$ avo install
```

to let Avocado place a deployment manifest file, called `Avofile`, in your project root folder. Then just open up the file in your editor of choice to customize your deployment process. The file is fully commented, giving you a basic understanding of how Avocado helps you to get your deployments done.

### Need more documentation?
I'm currently creating documents that both the end user and developers might find helpful.

### Authors and Contributors
The project is founded and maintained by @dprandzioch. You are welcome to contribute your changes and enhancements by just creating a pull request to the `develop` branch.

