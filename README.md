# Travis CI

## [Email Notifications](https://docs.travis-ci.com/user/notifications/#Configuring-email-notifications)

```yaml
notifications:
  email:
    recipients:
      - csh0034@gmail.com
    on_success: always # default: change
    on_failure: always # default: always
```

on_success 또는 on_failure 지정가능

- always: 항상 알림.
- never: 알림을 보내지 않음.
- change: 빌드 상태가 변경되면 알림을 보냄.
