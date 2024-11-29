# PETS Artifact Summary Repository for "The Impact of Mobile SDK Usage on Privacy and Data Protection"

This is the artifact respository to our publication `The Impact of Mobile SDK Usage on Privacy and Data Protection` accepted at PETS'25.
If you find this code helpful or the paper relevant to your work please cite us using the following bibtex.
This repository provides the summary of the whole org and you can simply clone it to have immediate access to all relevant code.

```
@inproceedings{PETS:Koch:2025,
 title={The Impact of Default Mobile SDK Usage on Privacy and Data Protection},
 author={Koch, Simon and Karl, Manuel and Kirchner, Robin and Wessels, Malte and Paschke, Anne and Johns, Martin},
 booktitle={Privacy Enhancing Technologies Symposium (PETS)},
 year={2025},
}
```

## Contents

During our research, we developed ten Android and iOS applications utilizing 5 different analytics and advertising SDKs.
We measured the traffic of those default implementations using the [scala-appanalyzer](https://github.com/App-Analysis/scala-appanalyzer) and analyzed the collected traffic using the [scala-plotalyzed](https://github.com/App-Analysis/scala-plotalyzer).
Both tools are constantly developed and managed using [their own org](https://github.com/App-Analysis).
For instructions on how to conduct measurements and analysis using the tools refer to that org.

This organization contains the measurement-plugin and analysis-plugin as well as the code of our sample applications in separate repositories for the differen SDKs and OS.
While each code compiles we replaced the identifiers used for each SDK with placeholders as those are tied to us personally.
Thus, to successfully run the apps you have to create your own account.
Furthermore, developing and deploying iOS applications requires an Apple Developer Account and Apple hardware to run the corresponding development tools.
Due to those hindrances we only provide the code as is and only inquire for the `available` artifact level.
We also added our plotting code with a requirements.txt for the required python packages. 
Using the analysis-plugin results in a json file that can be processed by this code.
