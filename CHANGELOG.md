# Change Log

## [0.8.4](https://github.com/thefactory/marathon-python/tree/0.8.4) (2016-07-20)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.8.3...0.8.4)

**Closed issues:**

- Can we get another Pypi release? [\#130](https://github.com/thefactory/marathon-python/issues/130)

**Merged pull requests:**

- Fix py3k regression in 0.8.3 [\#131](https://github.com/thefactory/marathon-python/pull/131) ([jimbobhickville](https://github.com/jimbobhickville))
- Expose id query param in list\_apps [\#129](https://github.com/thefactory/marathon-python/pull/129) ([moonkev](https://github.com/moonkev))

## [0.8.3](https://github.com/thefactory/marathon-python/tree/0.8.3) (2016-07-19)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.8.2...0.8.3)

**Closed issues:**

- New marathon application structure field [\#126](https://github.com/thefactory/marathon-python/issues/126)
- MarathonReadinessCheck class is absent [\#122](https://github.com/thefactory/marathon-python/issues/122)
- Supporting creating applications with a json file \(or json-formatted string, or json object\) [\#112](https://github.com/thefactory/marathon-python/issues/112)
- Task.ip\_addresses are not set properly [\#110](https://github.com/thefactory/marathon-python/issues/110)
- RuntimeError: maximum recursion depth exceeded in cmp when calling create\_app [\#60](https://github.com/thefactory/marathon-python/issues/60)

**Merged pull requests:**

- Try to fix java hostname issues [\#128](https://github.com/thefactory/marathon-python/pull/128) ([solarkennedy](https://github.com/solarkennedy))
- Issue126: secrets and taskKillGracePeriodSeconds Marathon.App fields … [\#127](https://github.com/thefactory/marathon-python/pull/127) ([dmajere](https://github.com/dmajere))
- Issue \#70: Remove resource\_name from get\_group [\#124](https://github.com/thefactory/marathon-python/pull/124) ([stj](https://github.com/stj))
- Type assertion for ReadinessCheck in MarathonApp.\_\_init\_\_ method added [\#123](https://github.com/thefactory/marathon-python/pull/123) ([dmajere](https://github.com/dmajere))
- Use requests.Session while communicating with Marathon. [\#121](https://github.com/thefactory/marathon-python/pull/121) ([Nihn](https://github.com/Nihn))
- Fix `Client.get\_version` method. [\#120](https://github.com/thefactory/marathon-python/pull/120) ([Nihn](https://github.com/Nihn))
- Handle HTTP errors without content graceful [\#119](https://github.com/thefactory/marathon-python/pull/119) ([stj](https://github.com/stj))
- Add local\_volumes to MarathonTask [\#118](https://github.com/thefactory/marathon-python/pull/118) ([usmanm](https://github.com/usmanm))
- Fix pep8 issues and strict flake8 check. [\#117](https://github.com/thefactory/marathon-python/pull/117) ([oilbeater](https://github.com/oilbeater))
- Don't die if no JSON found in response [\#116](https://github.com/thefactory/marathon-python/pull/116) ([usmanm](https://github.com/usmanm))
- Set fetch in MarathonApp. [\#115](https://github.com/thefactory/marathon-python/pull/115) ([oilbeater](https://github.com/oilbeater))
- Add in state to the task model [\#114](https://github.com/thefactory/marathon-python/pull/114) ([chuckwired](https://github.com/chuckwired))
- Add 'persistent' volume option [\#113](https://github.com/thefactory/marathon-python/pull/113) ([jimbobhickville](https://github.com/jimbobhickville))
- Issue110: MarathonTask.ip\_addresses attribute is set properly [\#111](https://github.com/thefactory/marathon-python/pull/111) ([dmajere](https://github.com/dmajere))
- Add message field for MarathonStatusUpdateEvent. [\#109](https://github.com/thefactory/marathon-python/pull/109) ([oilbeater](https://github.com/oilbeater))

## [0.8.2](https://github.com/thefactory/marathon-python/tree/0.8.2) (2016-06-14)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.8.1...0.8.2)

**Closed issues:**

- AttributeError on connection issues [\#106](https://github.com/thefactory/marathon-python/issues/106)
- Wrongly use version\_info as task\_stats [\#104](https://github.com/thefactory/marathon-python/issues/104)
- c.scale\_app\('myapp3', 2\) [\#102](https://github.com/thefactory/marathon-python/issues/102)
- AttributeError: module 'marathon' has no attribute 'MarathonClient' [\#100](https://github.com/thefactory/marathon-python/issues/100)
- when run list\_apps ,has  errors [\#99](https://github.com/thefactory/marathon-python/issues/99)

**Merged pull requests:**

- Make exception handling work with py3k [\#108](https://github.com/thefactory/marathon-python/pull/108) ([jimbobhickville](https://github.com/jimbobhickville))
- Add 'wipe' option to kill\_task methods [\#107](https://github.com/thefactory/marathon-python/pull/107) ([jimbobhickville](https://github.com/jimbobhickville))
- task\_stats bugfix and query improvements. [\#105](https://github.com/thefactory/marathon-python/pull/105) ([oilbeater](https://github.com/oilbeater))
- Change to\_json\(\) datatime format [\#103](https://github.com/thefactory/marathon-python/pull/103) ([oilbeater](https://github.com/oilbeater))
- add name attribute to port mapping [\#101](https://github.com/thefactory/marathon-python/pull/101) ([Rob-Johnson](https://github.com/Rob-Johnson))

## [0.8.1](https://github.com/thefactory/marathon-python/tree/0.8.1) (2016-04-21)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.8.0...0.8.1)

**Closed issues:**

- Does not understand readiness\_check\_results [\#94](https://github.com/thefactory/marathon-python/issues/94)
- Generate marathon-python from raml [\#86](https://github.com/thefactory/marathon-python/issues/86)
- Support Marathon 0.15.1 [\#84](https://github.com/thefactory/marathon-python/issues/84)

**Merged pull requests:**

- Added force option for kill\_given\_tasks [\#96](https://github.com/thefactory/marathon-python/pull/96) ([solarkennedy](https://github.com/solarkennedy))
- Support the deployments endpoint correctly in marathon 1.1.1 [\#95](https://github.com/thefactory/marathon-python/pull/95) ([solarkennedy](https://github.com/solarkennedy))

## [0.8.0](https://github.com/thefactory/marathon-python/tree/0.8.0) (2016-04-18)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.7.7...0.8.0)

**Closed issues:**

- 0.7.7 release [\#90](https://github.com/thefactory/marathon-python/issues/90)

**Merged pull requests:**

- Comply with pep8 betterer [\#93](https://github.com/thefactory/marathon-python/pull/93) ([solarkennedy](https://github.com/solarkennedy))
- Support marathon .15 and 1.1 [\#92](https://github.com/thefactory/marathon-python/pull/92) ([solarkennedy](https://github.com/solarkennedy))
- Add support for /v2/events stream [\#91](https://github.com/thefactory/marathon-python/pull/91) ([nuclon](https://github.com/nuclon))
- update for v2/queue and v2/apps?embed=apps.taskStats [\#89](https://github.com/thefactory/marathon-python/pull/89) ([bergerx](https://github.com/bergerx))

## [0.7.7](https://github.com/thefactory/marathon-python/tree/0.7.7) (2016-02-29)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.7.6...0.7.7)

**Merged pull requests:**

- restart endpoint [\#88](https://github.com/thefactory/marathon-python/pull/88) ([burakbostancioglu](https://github.com/burakbostancioglu))
- a small fix for fetching apps for marathon v0.15 [\#87](https://github.com/thefactory/marathon-python/pull/87) ([burakbostancioglu](https://github.com/burakbostancioglu))

## [0.7.6](https://github.com/thefactory/marathon-python/tree/0.7.6) (2016-02-12)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.7.5...0.7.6)

**Closed issues:**

- MarathonClient is not compatible with marathon 0.14.1-1.0.455.ubuntu1404 [\#81](https://github.com/thefactory/marathon-python/issues/81)
- Zero values in apps/groups doesnt work [\#75](https://github.com/thefactory/marathon-python/issues/75)
- does marathon-python supports marathon Version 0.11.1?  [\#66](https://github.com/thefactory/marathon-python/issues/66)
- Why MarathonDockerContainer.parameters is defined as dict? [\#47](https://github.com/thefactory/marathon-python/issues/47)

**Merged pull requests:**

- 0.14 support [\#85](https://github.com/thefactory/marathon-python/pull/85) ([itamaro](https://github.com/itamaro))
- Change MarathonDockerContainer.parameters to type list [\#83](https://github.com/thefactory/marathon-python/pull/83) ([fengyehong](https://github.com/fengyehong))
- Don't drop 0s when transforming to JSON [\#79](https://github.com/thefactory/marathon-python/pull/79) ([iksaif](https://github.com/iksaif))
- Itest fixes and stick to legacy travis infrastructure for now. [\#78](https://github.com/thefactory/marathon-python/pull/78) ([solarkennedy](https://github.com/solarkennedy))
- Modify list\_apps so user can input app\_id without the starting slash [\#71](https://github.com/thefactory/marathon-python/pull/71) ([fengyehong](https://github.com/fengyehong))
- Use the /v2/tasks/delete endpoint for taskkill [\#67](https://github.com/thefactory/marathon-python/pull/67) ([fengyehong](https://github.com/fengyehong))

## [0.7.5](https://github.com/thefactory/marathon-python/tree/0.7.5) (2015-12-09)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.7.4...0.7.5)

**Merged pull requests:**

- Release 0.7.5 for official Marathon 11 support [\#73](https://github.com/thefactory/marathon-python/pull/73) ([solarkennedy](https://github.com/solarkennedy))
- Added tests for killing tasks on an app [\#72](https://github.com/thefactory/marathon-python/pull/72) ([solarkennedy](https://github.com/solarkennedy))
- Provide proper compatability support for str/unicode in py3 [\#57](https://github.com/thefactory/marathon-python/pull/57) ([mattrobenolt](https://github.com/mattrobenolt))

## [0.7.4](https://github.com/thefactory/marathon-python/tree/0.7.4) (2015-11-20)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.7.3...0.7.4)

**Merged pull requests:**

- Use automatic changelog generation [\#69](https://github.com/thefactory/marathon-python/pull/69) ([solarkennedy](https://github.com/solarkennedy))
- Marathon 11 Support [\#68](https://github.com/thefactory/marathon-python/pull/68) ([solarkennedy](https://github.com/solarkennedy))

## [0.7.3](https://github.com/thefactory/marathon-python/tree/0.7.3) (2015-11-12)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.7.2...0.7.3)

**Closed issues:**

- When will you guys release 0.7.2 [\#62](https://github.com/thefactory/marathon-python/issues/62)
- 0.7.1 tag missing [\#61](https://github.com/thefactory/marathon-python/issues/61)

**Merged pull requests:**

- use the /v2/tasks endpoint for list\_tasks [\#65](https://github.com/thefactory/marathon-python/pull/65) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Remove call to logging.basicConfig [\#64](https://github.com/thefactory/marathon-python/pull/64) ([itamaro](https://github.com/itamaro))

## [0.7.2](https://github.com/thefactory/marathon-python/tree/0.7.2) (2015-09-18)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.7.0...0.7.2)

**Closed issues:**

- Marathon Json encoder can't handle unicode strings [\#50](https://github.com/thefactory/marathon-python/issues/50)
- Marathon app name validation is broken [\#45](https://github.com/thefactory/marathon-python/issues/45)
- New release for 8.2 compatibility [\#38](https://github.com/thefactory/marathon-python/issues/38)
- Task.app\_id is None when using c.get\_app\("xxx"\).tasks [\#9](https://github.com/thefactory/marathon-python/issues/9)

**Merged pull requests:**

- Updated to support Marathon 0.9.1 with get\_info\(\) calls [\#59](https://github.com/thefactory/marathon-python/pull/59) ([pyronicide](https://github.com/pyronicide))
- Add support for building with a wheel and cleanup setup.py [\#58](https://github.com/thefactory/marathon-python/pull/58) ([mattrobenolt](https://github.com/mattrobenolt))
- travis should run unit tests [\#55](https://github.com/thefactory/marathon-python/pull/55) ([Rob-Johnson](https://github.com/Rob-Johnson))
- implement \_\_eq\_\_ on base models + fix tests to be useful [\#54](https://github.com/thefactory/marathon-python/pull/54) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Fix deployments parsing [\#53](https://github.com/thefactory/marathon-python/pull/53) ([Rob-Johnson](https://github.com/Rob-Johnson))
- Added failing test and fix for unicode handling [\#52](https://github.com/thefactory/marathon-python/pull/52) ([solarkennedy](https://github.com/solarkennedy))
- Removed previously unused test framework in favor of tox + docker-compose version [\#49](https://github.com/thefactory/marathon-python/pull/49) ([solarkennedy](https://github.com/solarkennedy))
- Add accepted\_resource\_role kwarg for Marathon 0.9.0 support [\#48](https://github.com/thefactory/marathon-python/pull/48) ([keshavdv](https://github.com/keshavdv))
- Upstream merge - Add itest framework and fix regex [\#46](https://github.com/thefactory/marathon-python/pull/46) ([solarkennedy](https://github.com/solarkennedy))
- First pass at adding an itest framework [\#42](https://github.com/thefactory/marathon-python/pull/42) ([solarkennedy](https://github.com/solarkennedy))

## [0.7.0](https://github.com/thefactory/marathon-python/tree/0.7.0) (2015-07-06)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.15...0.7.0)

**Closed issues:**

- MarathonHealthCheck class doesn't support 0.8.2  [\#34](https://github.com/thefactory/marathon-python/issues/34)

**Merged pull requests:**

- Update endpoint docstring. [\#41](https://github.com/thefactory/marathon-python/pull/41) ([Poogles](https://github.com/Poogles))
- fixed variable name in list comprehension [\#39](https://github.com/thefactory/marathon-python/pull/39) ([AFriemann](https://github.com/AFriemann))
- Add validation to marathon app/group ids [\#37](https://github.com/thefactory/marathon-python/pull/37) ([mattrobenolt](https://github.com/mattrobenolt))
- adds ignore\_http1xx and forward compat kwargs to MarathonHealthCheck [\#36](https://github.com/thefactory/marathon-python/pull/36) ([mrtheb](https://github.com/mrtheb))
- Feature/event factory [\#32](https://github.com/thefactory/marathon-python/pull/32) ([kevinschoon](https://github.com/kevinschoon))

## [0.6.15](https://github.com/thefactory/marathon-python/tree/0.6.15) (2015-06-05)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.14...0.6.15)

**Merged pull requests:**

- Make `force\_pull\_image` actually work [\#33](https://github.com/thefactory/marathon-python/pull/33) ([mattrobenolt](https://github.com/mattrobenolt))

## [0.6.14](https://github.com/thefactory/marathon-python/tree/0.6.14) (2015-05-28)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.13...0.6.14)

**Closed issues:**

- forcePullImage not honored by marathon-python \(marathon 0.8.2 RC2\) [\#29](https://github.com/thefactory/marathon-python/issues/29)
- create\_app\(\) not working for docker container [\#28](https://github.com/thefactory/marathon-python/issues/28)
- Urgent BUG: to\_json\(\) is returning unexpected result under python3 version [\#26](https://github.com/thefactory/marathon-python/issues/26)
- portMapping isn't iterable [\#25](https://github.com/thefactory/marathon-python/issues/25)

**Merged pull requests:**

- Added forcePullImage parameter for the container model [\#31](https://github.com/thefactory/marathon-python/pull/31) ([solarkennedy](https://github.com/solarkennedy))
- Quick fix \#29 - add kwargs to MarathonDockerContainer.\_\_init\_\_ [\#30](https://github.com/thefactory/marathon-python/pull/30) ([g----](https://github.com/g----))
- Fixed \#26:Using try/except to get rid of use\_2to3 failing [\#27](https://github.com/thefactory/marathon-python/pull/27) ([vitan](https://github.com/vitan))

## [0.6.13](https://github.com/thefactory/marathon-python/tree/0.6.13) (2015-03-24)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.12...0.6.13)

**Merged pull requests:**

- Added get\_leader and delete\_leader functions [\#24](https://github.com/thefactory/marathon-python/pull/24) ([pradeepchhetri](https://github.com/pradeepchhetri))
- Fixed get\_info for marathon-0.8.1-RC2 [\#23](https://github.com/thefactory/marathon-python/pull/23) ([pradeepchhetri](https://github.com/pradeepchhetri))
- Added two app parameters - tasks\_healthy, tasks\_unhealthy \(marathon-0.8.1-RC2\) [\#21](https://github.com/thefactory/marathon-python/pull/21) ([pradeepchhetri](https://github.com/pradeepchhetri))
- Possibility to send the full object to Marathon on update [\#20](https://github.com/thefactory/marathon-python/pull/20) ([wndhydrnt](https://github.com/wndhydrnt))

## [0.6.12](https://github.com/thefactory/marathon-python/tree/0.6.12) (2015-03-07)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.11...0.6.12)

## [0.6.11](https://github.com/thefactory/marathon-python/tree/0.6.11) (2015-03-06)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.10...0.6.11)

**Merged pull requests:**

- Small changes to fix compatibility issues with Marathon 0.8.0 [\#19](https://github.com/thefactory/marathon-python/pull/19) ([cloudify](https://github.com/cloudify))

## [0.6.10](https://github.com/thefactory/marathon-python/tree/0.6.10) (2014-12-17)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.8...0.6.10)

**Merged pull requests:**

- Added optional ?force=true param to MarathonClient.delete\_deployment\(\) [\#18](https://github.com/thefactory/marathon-python/pull/18) ([mattcallanan](https://github.com/mattcallanan))
- Add parameters and privileged fields to Container model [\#17](https://github.com/thefactory/marathon-python/pull/17) ([gabrtv](https://github.com/gabrtv))
- apparently undocumented API in Marathon [\#16](https://github.com/thefactory/marathon-python/pull/16) ([elyast](https://github.com/elyast))

## [0.6.8](https://github.com/thefactory/marathon-python/tree/0.6.8) (2014-11-19)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.7...0.6.8)

## [0.6.7](https://github.com/thefactory/marathon-python/tree/0.6.7) (2014-11-18)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.6...0.6.7)

**Closed issues:**

- update\_app\(\) no-ops if Version is passed [\#14](https://github.com/thefactory/marathon-python/issues/14)

**Merged pull requests:**

- fixing issues with resources /v2/tasks, v2/info [\#15](https://github.com/thefactory/marathon-python/pull/15) ([elyast](https://github.com/elyast))

## [0.6.6](https://github.com/thefactory/marathon-python/tree/0.6.6) (2014-11-17)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.5...0.6.6)

**Closed issues:**

- scale\_app\(...\) calls update\_app\(...\) with only 1 argument [\#13](https://github.com/thefactory/marathon-python/issues/13)

## [0.6.5](https://github.com/thefactory/marathon-python/tree/0.6.5) (2014-11-14)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.4...0.6.5)

## [0.6.4](https://github.com/thefactory/marathon-python/tree/0.6.4) (2014-11-14)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.3...0.6.4)

**Merged pull requests:**

- Add MarathonHealthCheckResult Class to tasks File and Include it in MarathonTask [\#12](https://github.com/thefactory/marathon-python/pull/12) ([JTCunning](https://github.com/JTCunning))

## [0.6.3](https://github.com/thefactory/marathon-python/tree/0.6.3) (2014-10-10)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.2...0.6.3)

**Merged pull requests:**

- add service\_port argument [\#11](https://github.com/thefactory/marathon-python/pull/11) ([danielfrg](https://github.com/danielfrg))

## [0.6.2](https://github.com/thefactory/marathon-python/tree/0.6.2) (2014-10-09)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.1...0.6.2)

**Merged pull requests:**

- Add `LIKE` and `UNLIKE` constraint [\#10](https://github.com/thefactory/marathon-python/pull/10) ([iven](https://github.com/iven))

## [0.6.1](https://github.com/thefactory/marathon-python/tree/0.6.1) (2014-09-29)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.6.0...0.6.1)

## [0.6.0](https://github.com/thefactory/marathon-python/tree/0.6.0) (2014-09-29)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.5.1...0.6.0)

**Closed issues:**

- Support for HA nodes [\#8](https://github.com/thefactory/marathon-python/issues/8)

## [0.5.1](https://github.com/thefactory/marathon-python/tree/0.5.1) (2014-09-18)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.5.0...0.5.1)

## [0.5.0](https://github.com/thefactory/marathon-python/tree/0.5.0) (2014-09-18)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.4.0...0.5.0)

**Merged pull requests:**

- Bug Fix: Cannot define constraints with a tuple of strings [\#6](https://github.com/thefactory/marathon-python/pull/6) ([adgaudio](https://github.com/adgaudio))

## [0.4.0](https://github.com/thefactory/marathon-python/tree/0.4.0) (2014-08-19)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.3.1...0.4.0)

**Merged pull requests:**

- Throwing exceptions on 400s and 500s in \_do\_request [\#5](https://github.com/thefactory/marathon-python/pull/5) ([Codeacious](https://github.com/Codeacious))
- Fix container options not being sent to marathon [\#4](https://github.com/thefactory/marathon-python/pull/4) ([boffbowsh](https://github.com/boffbowsh))

## [0.3.1](https://github.com/thefactory/marathon-python/tree/0.3.1) (2014-08-05)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.2.9...0.3.1)

**Merged pull requests:**

- Raise exceptions instead of swallowing them silently [\#3](https://github.com/thefactory/marathon-python/pull/3) ([StephanErb](https://github.com/StephanErb))

## [0.2.9](https://github.com/thefactory/marathon-python/tree/0.2.9) (2014-08-04)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.2.7...0.2.9)

## [0.2.7](https://github.com/thefactory/marathon-python/tree/0.2.7) (2014-07-24)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.2.6...0.2.7)

## [0.2.6](https://github.com/thefactory/marathon-python/tree/0.2.6) (2014-07-24)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.2.5...0.2.6)

**Merged pull requests:**

- Updated README.md with correction to create\_app args [\#2](https://github.com/thefactory/marathon-python/pull/2) ([rasathus](https://github.com/rasathus))

## [0.2.5](https://github.com/thefactory/marathon-python/tree/0.2.5) (2014-07-02)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.2.3...0.2.5)

**Merged pull requests:**

- allowing stagedAt and startedAt keys to be null [\#1](https://github.com/thefactory/marathon-python/pull/1) ([Codeacious](https://github.com/Codeacious))

## [0.2.3](https://github.com/thefactory/marathon-python/tree/0.2.3) (2014-06-02)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.2.0...0.2.3)

## [0.2.0](https://github.com/thefactory/marathon-python/tree/0.2.0) (2014-04-28)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.1.1...0.2.0)

## [0.1.1](https://github.com/thefactory/marathon-python/tree/0.1.1) (2014-04-23)
[Full Changelog](https://github.com/thefactory/marathon-python/compare/0.1.0...0.1.1)

## [0.1.0](https://github.com/thefactory/marathon-python/tree/0.1.0) (2014-04-23)


\* *This Change Log was automatically generated by [github_changelog_generator](https://github.com/skywinder/Github-Changelog-Generator)*