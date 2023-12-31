# godot-template

[![version](https://img.shields.io/badge/4.x-blue?logo=godot-engine&logoColor=white&label=godot&style=for-the-badge)](https://godotengine.org "Made with godot")

Godot template repository for my programs

---

## How to use

> **Note**
> This template uses the [gpm](https://github.com/godot-package-manager#the-godot-package-manager).

- Click use this template button
- Clone your new repository
- Run install_addons.sh
- Add your files & change `FUNDING.yml`
- Commit & push

<details>
<summary>For itch.io depoloyment</summary>
<br>

Add a secret called `BUTLER_CREDENTIALS` with your [butler api key](https://itch.io/user/settings/api-keys).

</details>

<details>
<summary>For android builds</summary>
<br>

> **Note**
> The keystore user/alias is found automatically.
> If the `ANDROID_KEYSTORE_BASE64` field is not filled, the action will use the android debug keystore.

Add two secrets:

- `ANDROID_KEYSTORE_BASE64`
- `ANDROID_KEYSTORE_PASSWORD`

</details>

---

### CI Availability

|      windows       | ios |       linux        |      android       |        mac         |        html        |               |
| :----------------: | :-: | :----------------: | :----------------: | :----------------: | :----------------: | :-----------: |
|        :x:         | :x: |        :x:         |        :x:         |        :x:         | :heavy_check_mark: | github pages  |
| :heavy_check_mark: | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: |    itch.io    |
| :heavy_check_mark: | :x: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | :heavy_check_mark: | godot exports |
