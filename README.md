----
# ansible-role-app-pritunl
Installs [Pritunl](https://docs.pritunl.com/docs) VPN

## Defaulted variables
| Name | Type | Value | Comment |
| ---- | ---- | ----- | ------- |
| pritunl_keyserver | URL | `hkp://keyserver.ubuntu.com` ||
| pritunl_mongodb_uri | URL |  `mongodb://localhost:27017/pritunl` ||
| pritunl_pkg_dependencies | list(string) | see `defaults/main.yml` ||
| pritunl_pkg_name | string | pritunl ||
| pritunl_repo_path | string | see `defaults/main.yml` ||
| pritunl_repo_url | URL | `https://repo.pritunl.com/stable/apt` ||
| pritunl_signing_key | string | '7568D9BB55FF9E5287D586017AE645C0CF8E292A' ||
| pritunl_state | string | present | ..or absent |
| pritunl_svc_enabled | Boolean | true ||
| pritunl_svc_name | string | pritunl ||
| pritunl_svc_state | string | started | Systemd state |

****
