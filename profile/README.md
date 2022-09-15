[pepy-image]: https://pepy.tech/badge/braindecode
[pepy-url]: https://pepy.tech/project/braindecode

[![Join the chat at https://gitter.im/braindecodechat/community](https://badges.gitter.im/braindecodechat/community.svg)](https://gitter.im/braindecodechat/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)[![image](https://github.com/braindecode/braindecode/workflows/tests-and-docs/badge.svg)](https://github.com/braindecode/braindecode/actions)[![Doc build on CircleCI](https://circleci.com/gh/braindecode/braindecode.svg?style=svg)](https://circleci.com/gh/braindecode/braindecode)[![Code Coverage](https://codecov.io/gh/braindecode/braindecode/branch/master/graph/badge.svg)](https://codecov.io/gh/braindecode/braindecode)[![Downloads][pepy-image]][pepy-url]

![Braindecode Logo](https://raw.githubusercontent.com/braindecode/braindecode/master/docs/_static/braindecode.svg)


----

[GitHub](https://github.com/braindecode/braindecode) | [Tutorials](https://braindecode.org/master/auto_examples/index.html) | [Documentation](https://braindecode.org/master/) | [Chat](https://gitter.im/braindecodechat/community) 


Braindecode is an open-source Python toolbox for decoding raw
electrophysiological brain data with deep learning models. It includes
dataset fetchers, data preprocessing and visualization tools, as well as
implementations of several deep learning architectures and data
augmentations for analysis of EEG, ECoG and MEG.

For neuroscientists who want to work with deep learning and deep
learning researchers who want to work with neurophysiological data.
---

### Braindecode compatible with the [MNE](mne.tools/) ecosystem.

---

## Documentation

Documentation is online under <https://braindecode.org>, in the
stable, and dev versions under <https://braindecode.org/master>.

## Installation Braindecode

1.  Install pytorch from <http://pytorch.org/> (you don\'t need to
    install torchvision).
2.  Install [MOABB](https://github.com/NeuroTechX/moabb) via pip (needed
    if you want to use MOABB datasets utilities):

```bash
pip install moabb
```

3.  Install latest release of braindecode via pip:

```bash
pip install braindecode
```

alternatively, if you use conda, you could create a dedicated
environment with the following:

```bash
curl -O https://raw.githubusercontent.com/braindecode/braindecode/master/environment.yml
conda env create -f environment.yml
conda activate braindecode
```

alternatively, install the latest version of braindecode via pip:

```bash
pip install -U https://api.github.com/repos/braindecode/braindecode/zipball/master
```


