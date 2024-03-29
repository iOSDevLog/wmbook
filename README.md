![wmbook](https://repository-images.githubusercontent.com/191505403/6a63bc80-8d1d-11e9-8bd7-44aaa16ccdb9)

[![Build Status](https://travis-ci.org/iOSDevLog/wmbook.svg?branch=master)](https://travis-ci.org/iOSDevLog/wmbook)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/wmbook.svg)
![PyPI](https://img.shields.io/pypi/v/wmbook.svg)
![PyPI - License](https://img.shields.io/pypi/l/wmbook.svg)
![PyPI - Wheel](https://img.shields.io/pypi/wheel/wmbook.svg)
![PyPI - Downloads](https://img.shields.io/pypi/dm/wmbook.svg)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![Twitter](https://img.shields.io/twitter/url/https/github.com/iOSDevLog/wmbook.svg?style=social)](https://twitter.com/intent/tweet?text=Wow:&url=https%3A%2F%2Fgithub.com%2FiOSDevLog%2Fwmbook)

# wmbook

Machine Learning (Watermelon Book) 机器学习（西瓜书）

GitHub: [https://github.com/iOSDevLog/wmbook](https://github.com/iOSDevLog/wmbook)
PyPI: [https://travis-ci.org/iOSDevLog/wmbook](https://travis-ci.org/iOSDevLog/wmbook)

## 代码规范

### .vscode/settings.json

```json
{
  "python.pythonPath": "/Users/iosdevlog/.Envs/wmbook/bin/python",
  "python.linting.flake8Enabled": true,
  "python.formatting.provider": "yapf",
  "python.linting.flake8Args": ["--max-line-length=248"],
  "python.linting.pylintEnabled": false
}
```

- 字符串使用双引号： **""**

## 安装

```sh
pip install wmbook
```

## 开发

### 本地开发

```sh
pip3 install -e .
```

### 测试

```sh
pytest
```

### 发布

```sh
python3 setup.py sdist bdist_wheel
twine upload dist/*
```

### 生成 CHANGELOG

```sh
npm install -g conventional-changelog-cli
./version.sh
```

## 联系方式

网站: [http://2019.iosdevlog.com/](https://2019.iosdevlog.com/)

微信公众号: AI 开发日志

![wmbook](https://2019.iosdevlog.com/uploads/wmbook.jpg)

## License

wmbook is released under the MIT license. See [LICENSE](LICENSE) for details.
