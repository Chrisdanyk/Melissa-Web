## Melissa-Web
Melissa-Web is the web interface for the [Melissa-Core](https://github.com/Melissa-AI/Melissa-Core) repository. It provides the user a web-based interface for operating Melissa on their systems.

### Installation
The installation steps are esentially the same as that of Melissa-Core, however, there are a few changes to the `requirements.txt` file.

#### For OS X Systems
Clone the project using `git`. You can install git and other CLI developer tools by running the following commands:

```
xcode-select --install
```

You will need to install [PortAudio](http://www.portaudio.com/download.html) and [PyAudio](http://people.csail.mit.edu/hubert/pyaudio/). Now run the following commands:

```
git clone https://github.com/tanay1337/Melissa.git
cd Melissa
pip install -r requirements.txt --allow-external pywapi --allow-unverified pywapi
cp profile.yaml.default profile.yaml
cp memory.db.default memory.db
```

#### For Linux Systems
Install `git` and `espeak` using your distribution's package manager or build them from their binary files. Follow the same steps as OS X's installation system, starting from installing PortAudio and PyAudio. To play music, you will have to install [mpg123](http://www.mpg123.de).

### Configuration
Once you have successfully set up your development environment, open `profile.yaml` to customise the file and add details about yourself.

### Usage Guide
Follow [this](https://github.com/Melissa-AI/Melissa-Core/blob/master/USAGE.md) link for reading the Usage aka Dating Guide.

### Contributing

After forking `Melissa-AI/Melissa-Web` and making the appropriate changes, open an issue and a pull request. After testing the issue/pull request, your request will be merged.

### Licence

[The MIT License (MIT)](https://github.com/Melissa-AI/Melissa-Core/blob/master/LICENSE.md)
