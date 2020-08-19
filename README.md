# :copyright: Edge Gravity Mechanical Keyboard - TODOs

:star: **本仓库主要用于存放本组织的待做事项、闪念、想法、项目进度和记事……**

## :memo: 待做事项

- [ ] :gear: PCB
  - [ ] 主控板 - 原理图
  - [ ] 主控板 - PCB Layout
  - [ ] 键盘底板 - 原理图
  - [ ] 键盘底板 - PCB Layout
- [ ] :construction: 主控软件开发（C、C++）
  - [ ] QSPI NorFlash 驱动
  - [ ] FMC SDRAM 驱动
  - [ ] LTDC 驱动
  - [ ] TouchGFX 开发
  - [ ] 键轴阵列驱动
  - [ ] IAP Bootloader
- [ ] :computer: 上位机软件开发（C# WPF、Python）
  - [ ] 灯效配置生成（Python）
  - [ ] 交互界面
    - [ ] 系统信息采集
      - [ ] CPU 名称、频率、占用率、温度
      - [ ] GPU 名称、显存容量、频率、占用率、温度
      - [ ] DDR 内存频率
      - [ ] 硬盘信息
      - [ ] 时间反馈（给主控）
    - [ ] RGB 灯效配置导入
    - [ ] 键盘固件 IAP 升级
- [ ] :art: 美工 UX/UI
- [ ] :signal_strength: 网络相关
  - [ ] 前端
  - [ ] 后台

## :bulb: 闪念&想法

## :bookmark_tabs: 项目进度

## :hammer: 硬件

### :triangular_flag_on_post: 核心板硬件

- [ ] 物料选型
  - [ ] MCU：STM32F767IGT6（Cortex-M7，LQFP-176）
    - [ ] QSPI - NorFlash：W25Q256JVFIQ（32 MBytes，SOIC-16）
    - [ ] FMC - SDRAM：IS42S32400F-6TLI TSOP-86（16 MBytes，32 bit）
    - [ ] LTDC - 5 吋 RGB 24bit 显示屏（TN/IPS）
    - [ ] SDMMC - TF 卡
    - [ ] USB
    - [ ] USART
    - [ ] GPIO
      - [ ] 用户按键
      - [ ] LED 指示灯
    - [ ] 传感器
      - [ ] I2C - 温湿度传感器 SHT30-DIS（ADDR引脚接地时地址为 0x44，接电源时地址为0x45）
      - [ ] I2C - 光照度传感器 BH1750FVI（ADDR引脚接地时地址为 0x46，接电源时地址为0xB8）
      - [ ] ADC - 咪头（采集环境声音，可做音乐频谱）
- [ ] 仿真器（SWD）
  - [ ] STLink-V3
  - [ ] JLink-V9

### :keyboard: 机械键盘本体硬件

- 轴体 Mechanical Switches
- 键帽 Keycaps
- 定位板 Keyboard Plate
- 外壳 Keyboard Cases
  - 上盖
  - 底座
- 平衡杆 Stabilizer
