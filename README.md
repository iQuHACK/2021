# 2021
## Submit a new idea by opening a [new issue](https://github.com/iQuHACK/2021/issues/new "go to New Issue")

[![Issue Help](static/issue_help.png)](https://github.com/iQuHACK/2021/issues "go to Issues")

Keep in mind these ideas are open to the public and not regulated.

## Projects GitHub Instructions
All teams will have a git repository at `https://github.com/iQuHACK/2021_<team_name>`.
The initial team name will just be `team##` (e.g. `team03`).

### Workflow
1. Complete and submit the [team formation form](https://forms.gle/yhBwRT78Vtt1S5nL8).
2. Clone your repository.
3. Begin hacking!
4. Before the submission deadline, make sure you push/merge your final work to the `main` branch. You will lose push permission right at the deadline.

### Team Names
You can change your team's name at any point by contacting one of the staff through Slack or email iquhack@mit.edu.
We will update your repo's name accordingly with the most recent submission.

### After the event
After submission closes, we will remove your team's access to that repo and make it public.
**Feel free to fork it and keep working on it after the event!**

## Resources
### Getting Started
We recommend using conda for your project. If you aren't familiar with it, once setup you barely have to interact with it! Checkout their installation instructions [here](https://docs.conda.io/projects/conda/en/latest/user-guide/install/).

We have seen some issues using python 3.8, so we recommend using **Python 3.7**.
For example, if you want your environment named `iQuHACK`:
```
conda create -n iQuHACK python=3.7
pip install qiskit
```
To load this environment: `conda activate iQuHACK`.

If `conda` cannot be found (and you are on a unix-like system), you most likely have *not* initialized it during installing.
You can do this by running the init script in the installation directory:
```
source <path to conda>/bin/activate
conda init zsh
```
Then you should be good to go. MacOS Catalina now uses `zsh` shell instead of `bash`, but put your appropriate shell name there.

#### iQuHACK
- [iquhack.slack.com](https://iquhack.slack.com/) (check your email for invite link, or email iquhack@mit.edu)
- [iQuHACK site](https://www.iquise.mit.edu/iQuHACK)

#### Resources
- [D-Wave Tutorials](https://www.dwavesys.com/resources/tutorials)
- [ionQ Technology](https://ionq.com/technology)
- [Qiskit Tutorials](https://qiskit.org/learn/)
- [Qiskit Examples](https://qiskit.org/experiments/)
- [Cirq Tutorials](https://quantumai.google/cirq)

<img src="static/qbraid_logo.png" height=30px></img>
**[qBraid](https://www.qbraid.com/)** has generously prepared a virtual environment with the above packages and dependencies installed as well as some tutorial jupyter notebooks.
After you [create an account](https://account.qbraid.com/join ), select the iQuHACK package and you’re ready to go!
