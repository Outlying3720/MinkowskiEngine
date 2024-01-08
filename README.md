[pypi-image]: https://badge.fury.io/py/MinkowskiEngine.svg
[pypi-url]: https://pypi.org/project/MinkowskiEngine/
[pypi-download]: https://img.shields.io/pypi/dm/MinkowskiEngine
[slack-badge]: https://img.shields.io/badge/slack-join%20chats-brightgreen
[slack-url]: https://join.slack.com/t/minkowskiengine/shared_invite/zt-piq2x02a-31dOPocLt6bRqOGY3U_9Sw

# Minkowski Engine

[![PyPI Version][pypi-image]][pypi-url] [![pypi monthly download][pypi-download]][pypi-url] [![slack chat][slack-badge]][slack-url]

Minor patch to fix Minkoski Engine build error on pytorch>1.8

Install Step

```
git clone https://github.com/Outlying3720/MinkowskiEngine
cd MinkowskiEngine

apt install build-essential python3-dev libopenblas-dev
pip install . -v --no-deps --config-settings='--install-option="--force_cuda" --install-option="--blas=openblas"'
```