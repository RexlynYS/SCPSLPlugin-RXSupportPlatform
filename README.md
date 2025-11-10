# RXSupportPlatform [Beta]

## 插件依赖安装

> ⚠️ 必须安装以下依赖插件

1. **AudioPlayer**  
   下载地址：[https://github.com/Killers0992/AudioPlayerApi](https://github.com/Killers0992/AudioPlayerApi)  
   安装路径：将 `AudioPlayer.dll` 放入 Exiled 框架的 dependencies 文件夹  
   ```
   \AppData\Roaming\EXILED\Plugins\dependencies
   ```

2. **ProjectMER**  
   下载地址：[https://github.com/Michal78900/ProjectMER](https://github.com/Michal78900/ProjectMER)  
   安装步骤：  
   - 将 ProjectMER 安装到 LabAPI 的全局插件文件夹  
     ```
     \AppData\Roaming\SCP Secret Laboratory\LabAPI\plugins\global
     ```
   - 安装完成后**重启服务器**  
   - 打开原理图配置目录  
     ```
     \AppData\Roaming\SCP Secret Laboratory\LabAPI\configs\ProjectMER\Schematics
     ```
   - 将支援平台原理图文件夹（名称：`ZYPT`）复制到上述目录


## 插件本体安装

1. 将 `RXSupportPlatform.dll` 放入 Exiled 框架插件目录  
   ```
   \AppData\Roaming\EXILED\Plugins
   ```


## 音频文件安装

1. 安装插件本体后**重启服务器**，插件会自动生成音频文件夹  
   路径：  
   ```
   \AppData\Roaming\EXILED\RXSupportPlatformAudio
   ```

2. 音频文件夹结构：  
   - 基金会敌对音频文件夹  
   - 基金会人员音频文件夹  

3. 分别放入对应文件：  
   - 将 `enemy_spawn.ogg` 放入 **基金会敌对音频文件夹**  
   - 将 `staff_spawn.ogg` 放入 **基金会人员音频文件夹**  

4. 再次**重启服务器**，完成安装


## 自定义配置

1. 首次启动插件后，会在 Exiled 配置目录生成配置文件  
   路径：  
   ```
   \AppData\Roaming\EXILED\Configs\Plugins\rx_support_platform
   ```

2. 可在配置文件中自定义插件功能（个性化设置）


## 关于插件

- 代码开发：Rexlyn_佑上  
- 地图（MER原理图）：Anaxiar  
- 感谢 [LY-Breach项目] 所有成员  

> ⚠️ 注意：该插件仍处于测试阶段，功能尚未完善，正式版将公开源码。
