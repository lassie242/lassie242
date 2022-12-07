

{
    "_readme": [
        "This file locks the dependencies of your project to a known state",
        "Read more about it at https://getcomposer.org/doc/01-basic-usage.md#composer-lock-the-lock-file",
        "This file is @generated automatically"
    ],
    "content-hash": "6ef64f6b8597686762d650caf4a63f9d",
    "packages": [
        {
            "name": "athlon1600/php-proxy-plugin-bundle",
            "version": "v1.0",
            "source": {
                "type": "git",
                "url": "https://github.com/Athlon1600/php-proxy-plugin-bundle.git",
                "reference": "feb4467bb78a0c31ae26acdbdb10847ab4c50c7f"
            },
            "dist": {
                "type": "zip",
                "url": "https://api.github.com/repos/Athlon1600/php-proxy-plugin-bundle/zipball/feb4467bb78a0c31ae26acdbdb10847ab4c50c7f",
                "reference": "feb4467bb78a0c31ae26acdbdb10847ab4c50c7f",
                "shasum": ""
            },
            "require": {
                "athlon1600/youtube-downloader": "^1.0"
            },
            "type": "library",
            "autoload": {
                "psr-4": {
                    "Proxy\\Plugin\\": "src/"
                },
                "files": [
                    "src/utils.php"
                ]
            },
            "license": [
                "MIT"
            ],
            "description": "A collection of useful plugins to be used with php-proxy",
            "support": {
                "source": "https://github.com/shirtjs/php-proxy-plugin-bundle/tree/v1.0"
            },
            "time": "2017-11-19T18:22:17+00:00"
        },
        {
            "name": "athlon1600/youtube-downloader",
            "version": "v1.0.1",
            "source": {
                "type": "git",
                "url": "https://github.com/Athlon1600/youtube-downloader.git",
                "reference": "50fc4f3ac7e2daf002b9ce21aee95252f87b3ae9"
            },
            "dist": {
                "type": "zip",
                "url": "https://api.github.com/repos/Athlon1600/youtube-downloader/zipball/50fc4f3ac7e2daf002b9ce21aee95252f87b3ae9",
                "reference": "50fc4f3ac7e2daf002b9ce21aee95252f87b3ae9",
                "shasum": ""
            },
            "require": {
                "ext-curl": "*"
            },
            "type": "library",
            "autoload": {
                "files": [
                    "src/YouTubeDownloader.php"
                ]
            },
            "notification-url": "https://packagist.org/downloads/",
            "license": [
                "MIT"
            ],
            "description": "PHP powered alternative for youtube-dl",
            "keywords": [
                "download youtube",
                "download youtube videos",
                "youtube downloader"
            ],
            "time": "2017-02-26T19:17:47+00:00"
        },
        {
            "name": "shirtjs/php-proxy",
            "version": "dev-master",
            "source": {
                "type": "git",
                "url": "https://github.com/shirtjs/php-proxy.git",
                "reference": "b9c681e90316224c46de256761358f6b039ba8eb"
            },
            "dist": {
                "type": "zip",
                "url": "https://api.github.com/repos/shirtjs/php-proxy/zipball/b9c681e90316224c46de256761358f6b039ba8eb",
                "reference": "b9c681e90316224c46de256761358f6b039ba8eb",
                "shasum": ""
            },
            "require": {
                "ext-curl": "*"
            },
            "suggest": {
                "predis/predis": "For caching purposes"
            },
            "type": "library",
            "autoload": {
                "psr-4": {
                    "Proxy\\": "src/"
                },
                "files": [
                    "src/helpers.php"
                ]
            },
            "license": [
                "MIT"
            ],
            "homepage": "https://www.php-proxy.com/",
            "keywords": [
                "php proxy",
                "php proxy script",
                "php web proxy",
                "proxy script",
                "web proxy"
            ],
            "support": {
                "source": "https://github.com/shirtjs/php-proxy/tree/master"
            },
            "time": "2018-05-04T18:09:34+00:00"
        }
    ],
    "packages-dev": [],
    "aliases": [],
    "minimum-stability": "stable",
    "stability-flags": {
        "shirtjs/php-proxy": 20
    },
    "prefer-stable": false,
    "prefer-lowest": false,
    "platform": {
        "ext-mbstring": "^7.2",
        "ext-gd": "^7.2",
        "ext-sqlite3": "^7.2",
        "ext-imagick": "*"
    },
    "platform-dev": []
}
Footer

