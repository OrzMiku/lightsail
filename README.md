# Lightsail MC Server

## 扩展包说明

`survival/packs` 文件夹包含了服务器的可选扩展包，您可以根据需要选择安装。

### 数据包 (Datapacks)

- 位于 `survival/packs/datapacks` 目录下的 `.zip` 文件是数据包。
- 要安装数据包，请将这些 `.zip` 文件移动到您的生存模式世界文件夹内的 `datapacks` 目录中 (通常是 `survival/world/datapacks`，但具体路径取决于您的世界名称，请自行确认)。

### 模组 (Mods)

- 位于 `survival/packs` 目录下的其他子文件夹（例如 `essentials`, `modifiers`, `QoLs`, `structures`, `terrains`）中包含的是模组文件（`.jar` 文件）。
- 要安装这些模组，请将相应的 `.jar` 文件移动到 `survival/mods` 文件夹中。

## 服务器名称修改

如需修改服务器在服务器列表中的显示名称和 TAB 列表中的名称，请编辑以下配置文件：

1. **服务器列表显示名称 (MOTD):**
    - 文件路径: [`velocity/plugins/minimotd-velocity/main.conf`](velocity/plugins/minimotd-velocity/main.conf)
    - 在此文件中查找并修改 MOTD相关的设置。

2. **TAB列表显示名称:**
    - 文件路径: [`velocity/plugins/tab/config.yml`](velocity/plugins/tab/config.yml) 和 [`velocity/plugins/tab/animations`](velocity/plugins/tab/animations.yml)
    - 在此文件中查找并修改与服务器名称或 TAB 显示相关的设置。

请确保在编辑配置文件后重启 Velocity 代理服务器和/或 Fabric 服务器以使更改生效。
