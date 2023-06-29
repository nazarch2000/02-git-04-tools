# Домашнее задание к занятию «Инструменты Git»

------

## Задание

В клонированном репозитории:

1. Найдите полный хеш и комментарий коммита, хеш которого начинается на `aefea`.
![image](https://github.com/nazarch2000/02-git-04-tools/assets/106932460/2666b601-fbd1-4578-95bd-e40671868ff1)

2. Ответьте на вопросы.

* Какому тегу соответствует коммит `85024d3`?
![image](https://github.com/nazarch2000/02-git-04-tools/assets/106932460/76947b2b-a8cc-445f-887e-c13b342b51d1)

* Сколько родителей у коммита `b8d720`? Напишите их хеши.
![image](https://github.com/nazarch2000/02-git-04-tools/assets/106932460/ad868736-0b7a-49f5-a9fc-5019d67a2e8e)

* Перечислите хеши и комментарии всех коммитов, которые были сделаны между тегами  v0.12.23 и v0.12.24.

```
commit b14b74c4939dcab573326f4e3ee2a62e23e12f89

    [Website] vmc provider links

commit 3f235065b9347a758efadc92295b540ee0a5e26e

    Update CHANGELOG.md

commit 6ae64e247b332925b872447e9ce869657281c2bf

    registry: Fix panic when server is unreachable

    Non-HTTP errors previously resulted in a panic due to dereferencing the
    resp pointer while it was nil, as part of rendering the error message.
    This commit changes the error message formatting to cope with a nil
    response, and extends test coverage.

    Fixes #24384

commit 5c619ca1baf2e21a155fcdb4c264cc9e24a2a353

    website: Remove links to the getting started guide's old location

    Since these links were in the soon-to-be-deprecated 0.11 language section, I
    think we can just remove them without needing to find an equivalent link.

commit 06275647e2b53d97d4f0a19a0fec11f6d69820b5

    Update CHANGELOG.md

commit d5f9411f5108260320064349b757f55c09bc4b80

    command: Fix bug when using terraform login on Windows

commit 4b6d06cc5dcb78af637bbb19c198faff37a066ed

    Update CHANGELOG.md

commit dd01a35078f040ca984cdd349f18d0b67e486c35

    Update CHANGELOG.md

commit 225466bc3e5f35baa5d07197bbc079345b77525e

    Cleanup after v0.12.23 release
```

* Найдите коммит, в котором была создана функция `func providerSource`, её определение в коде выглядит так: `func providerSource(...)` (вместо троеточия перечислены аргументы).
![image](https://github.com/nazarch2000/02-git-04-tools/assets/106932460/5d49420d-6037-4443-80bb-562b8bc433e6)

* Найдите все коммиты, в которых была изменена функция `globalPluginDirs`.
![image](https://github.com/nazarch2000/02-git-04-tools/assets/106932460/c07fa037-c1cb-47fd-b7bd-bbdeda2350da)

* Кто автор функции `synchronizedWriters`? 
![image](https://github.com/netology-code/sysadm-homeworks/assets/106932460/3c76b02f-06d1-47b3-8f88-15c503e6a0cc)

*В качестве решения ответьте на вопросы и опишите, как были получены эти ответы.*


