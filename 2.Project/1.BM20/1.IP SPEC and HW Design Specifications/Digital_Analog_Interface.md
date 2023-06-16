Digital_Analog_Interface

| name                   | wid th | dir  | default | scan value | name in diag        | comment         |
| :--------------------- | ------ | ---- | ------- | ---------- | ------------------- | --------------- |
| DRSTB                  | 1      | I    |         |            |                     |                 |
| CLK_256K               | 1      | I    |         |            |                     | 50% duty        |
| CLK_32M                | 1      | I    |         |            |                     |                 |
| CLK_32M_OK             | 1      | I    | 0       |            |                     |                 |
| SCL                    | 1      | O    | 0       |            |                     |                 |
| SDA_OUT                | 1      | O    | 0       |            |                     |                 |
| SDA_IN                 | 1      | I    |         |            |                     |                 |
| I2C_MAS_EN             | 1      | O    | 0       |            |                     |                 |
| TRIM_EN                | 1      | O    | 0       |            |                     | Test mode       |
| TMREG_EN               | 1      | O    | 0       |            |                     | Test mode       |
| TM_REG1                | 8      | O    |         |            | TMREG_REG           | Test mode       |
| TM_REG2                | 8      | O    |         |            | TMREG_REG           | Test mode       |
| TM_REG3                | 8      | O    |         |            | TMREG_REG           | Test mode       |
| TM_REG4                | 8      | O    |         |            | TMREG_REG           | Test mode       |
| TM_REG5                | 8      | O    |         |            | TMREG_REG           | Test mode       |
| TM_REG6                | 8      | O    |         |            | TMREG_REG           | Test mode       |
| TM_REG7                | 8      | O    |         |            | TMREG_REG           | Test mode       |
| TM_REG8                | 8      | O    |         |            | TMREG_REG           | Test mode       |
| TM_REG9                | 8      | O    |         |            | TMREG_REG           | Test mode       |
| TM_REG10               | 8      | O    |         |            | TMREG_REG           | Test mode       |
| A2D_COM_MINUS_N        | 1      | I    | 0       |            | A2D_RX              | Daisy chain     |
| A2D_COM_PLUS_N         | 1      | I    | 0       |            | A2D_RX              | Daisy chain     |
| A2D_COM_MINUS_S        | 1      | I    | 0       |            | A2D_RX              | Daisy chain     |
| A2D_COM_PLUS_S         | 1      | I    | 0       |            | A2D_RX              | Daisy chain     |
| A2D_WAKE_UP_N          | 1      | I    |         |            | WAKE_TONE_DET       | TONE_CTRL       |
| A2D_WAKE_UP_S          | 1      | I    |         |            | WAKE_TONE_DET       | TONE_CTRL       |
| A2D_STA_DET_N          | 1      | I    |         |            | STA_TONE_DET        | TONE_CTRL       |
| A2D_STA_DET_S          | 1      | I    |         |            | STA_TONE_DET        | TONE_CTRL       |
| D2A_CLR_WAKEUP         | 1      | O    | 0       |            |                     | TONE_CTRL       |
| TONE_CLK               | 1      | O    | 0       |            |                     | TONE_CTRL       |
| TONE_POLAR             | 1      | O    | 0       |            |                     | TONE_CTRL       |
| TONE_TRANS_EN_N        | 1      | O    | 0       |            | TONE_TRANS_EN       | TONE_CTRL       |
| TONE_TRANS_EN_S        | 1      | O    | 0       |            | TONE_TRANS_EN       | TONE_CTRL       |
| HB_TONE_DET            | 1      | I    |         |            |                     | 120us high time |
| D2A_RX_EN_N            | 1      | O    | 1       |            | D2A_RX_EN           | Daisy chain     |
| D2A_TX_EN_N            | 1      | O    | 0       |            | D2A_TX_EN           | Daisy chain     |
| D2A_RX_EN_S            | 1      | O    | 1       |            | D2A_RX_EN           | Daisy chain     |
| D2A_TX_EN_S            | 1      | O    | 0       |            | D2A_TX_EN           | Daisy chain     |
| D2A_WR_COM_MINUS       | 1      | O    | 0       |            | D2A_TX              | Daisy chain     |
| D2A_WR_COM_PLUS        | 1      | O    | 0       |            | D2A_TX              | Daisy chain     |
| D2A_TOP_DEV            | 1      | O    |         |            | COMM_DIG_SETTING    | REG             |
| DIR_SEL                | 1      | O    |         |            | COMM_DIG_SETTING    | REG             |
| DEV_ADD                | 7      | O    |         |            | COMM_DIG_SETTING    | REG             |
| DEV_NUM                | 7      | O    |         |            | COMM_DIG_SETTING    | REG             |
| ADD_W_EN               | 1      | O    |         |            | COMM_DIG_SETTING    | REG             |
| TOP_DEV_LATCH          | 1      | I    |         |            | COMM_DIG_SETTING    | REG             |
| DIR_SEL_LATCH          | 1      | I    |         |            | COMM_DIG_SETTING    | REG             |
| DEV_ADD_LATCH          | 7      | I    |         |            | COMM_DIG_SETTING    | REG             |
| DEV_NUM_LATCH          | 7      | I    |         |            | COMM_DIG_SETTING    | REG             |
| VAA_OV                 | 1      | I    |         |            | VAA_OVUV            | FLT_REG         |
| VAA_UV                 | 1      | I    |         |            | VAA_OVUV            | FLT_REG         |
| VDD_OV                 | 1      | I    |         |            | VDD_OVUV            | FLT_REG         |
| VDD_UV                 | 1      | I    |         |            | VDD_OVUV            | FLT_REG         |
| CP_OV                  | 1      | I    |         |            | CP_OVUV             | FLT_REG         |
| CP_UV                  | 1      | I    |         |            | CP_OVUV             | FLT_REG         |
| AGND_OW                | 1      | I    |         |            |                     | FLT_REG         |
|                        |        |      |         |            |                     |                 |
| RST_LCTO_SD_LATCH      | 1      | O    |         |            | RSTB_XXX_LATCH      | REG             |
| RST_CLK_256K_OKB_LATCH | 1      | O    |         |            | RSTB_XXX_LATCH      | REG             |
| RST_VDD_OKB_LATCH      | 1      | O    |         |            | RSTB_XXX_LATCH      | REG             |
| RST_VAA_OKB_LATCH      | 1      | O    |         |            | RSTB_XXX_LATCH      | REG             |
| RST_VDD_OV_LATCH       | 1      | O    |         |            | RSTB_XXX_LATCH      | REG             |
| RST_VDD_UV_LATCH       | 1      | O    |         |            | RSTB_XXX_LATCH      | REG             |
| LCTO_SD_LATCH          | 1      | I    |         |            | XXX_LATCH           | REG             |
| CLK_256K_OKB_LATCH     | 1      | I    |         |            | XXX_LATCH           | REG             |
| VDD_OKB_LATCH          | 1      | I    |         |            | XXX_LATCH           | REG             |
| VAA_OKB_LATCH          | 1      | I    |         |            | XXX_LATCH           | REG             |
| VDD_OV_LATCH           | 1      | I    |         |            | XXX_LATCH           | REG             |
| VDD_UV_LATCH           | 1      | I    |         |            | XXX_LATCH           | REG             |
|                        |        |      |         |            |                     |                 |
| BIST_REF_EN            | 1      | O    |         |            |                     | CMP_BIST_CTRL   |
| BIST_REF_EN_EARLY      | 1      | O    |         |            |                     | CMP_BIST_CTRL   |
| VDD_OV_BIST            | 1      | I    |         |            | VDD_OVUV_BIST       | CMP_BIST_CTRL   |
| VDD_UV_BIST            | 1      | I    |         |            | VDD_OVUV_BIST       | CMP_BIST_CTRL   |
|                        |        |      |         |            |                     |                 |
| D2A_LCTO_SEL01         | 1      | O    |         |            | LCTO_SEL            | POWER           |
| D2A_LCTO_SEL10         | 1      | O    |         |            | LCTO_SEL            | POWER           |
| D2A_LONG_TO            | 1      | O    |         |            | CLK_256K            | POWER           |
| D2A_TO_SD              | 1      | O    |         |            |                     | POWER           |
| D2A_TO_SLEEP           | 1      | O    |         |            |                     | POWER           |
|                        |        |      |         |            |                     |                 |
| FLT_WAKE               | 1      | O    |         |            |                     | POWER           |
| A2D_SLEEP_1P8          | 1      | I    |         |            | SLEEP               | POWER           |
|                        |        |      |         |            |                     |                 |
| MON_WAKE               | 1      | O    |         |            |                     | CYC_WAKE        |
|                        |        |      |         |            |                     |                 |
| CB_EN                  | 1      | O    |         |            |                     | CELL_BALANCE    |
| CB_TWARN_THRESH        | 4      | O    |         |            |                     | CELL_BALANCE    |
| CB_CH_EN               | 18     | O    |         |            |                     | CELL_BALANCE    |
| JOT                    | 1      | I    |         |            |                     | CELL_BALANCE    |
|                        |        |      |         |            |                     |                 |
| FLT_TONE_DET           | 1      | I    |         |            |                     |                 |
|                        |        |      |         |            |                     |                 |
| CS_EN_MANU             | 19     | O    |         |            |                     |                 |
| GPIO_PUPD              | 12     | O    |         |            |                     | GPIO            |
| GPIO_PUPD_EN           | 12     | O    |         |            |                     | GPIO            |
| WEAK_PUPD              | 12     | O    |         |            |                     | GPIO            |
| WEAK_PUPD_EN           | 12     | O    |         |            |                     | GPIO            |
| GPIO_AS_IN_EN          | 12     | O    |         |            |                     | GPIO            |
| GPIO_HL                | 12     | I    |         |            |                     | GPIO            |
| CS_EN_AUTO_SINK        | 1      | O    |         |            | CS_EN_AUTO          |                 |
| CS_EN_AUTO_SOURCE      | 1      | O    |         |            | CS_EN_AUTO          |                 |
|                        |        |      |         |            |                     |                 |
| SPI_EN                 | 1      | I    |         |            |                     | For bridge      |
| A2D_SPI_SCLK           | 1      | I    |         |            |                     | For bridge      |
| A2D_SPI_MOSI           | 1      | I    |         |            |                     | For bridge      |
| A2D_SPI_CSB            | 1      | I    |         |            |                     | For bridge      |
| D2A_SPI_MISO           | 1      | O    |         |            |                     | For bridge      |
| D2A_SPI_SPI_DRY        | 1      | O    |         |            |                     | For bridge      |
|                        |        |      |         |            |                     |                 |
| D2A_CELL_ADC_EN        | 1      | O    | 0       |            |                     |                 |
| ADC_CLK                | 1      | O    | 0       |            |                     |                 |
| ADC_CLK_H              | 1      | O    | 0       |            |                     |                 |
| ADC_POLAR              | 1      | O    | 0       |            | ADC_SEQ             |                 |
| ADC_RST_INT            | 1      | O    | 0       |            | ADC_SEQ             |                 |
| ADC_EN_SH_VIN          | 1      | O    | 0       |            | ADC_SEQ             |                 |
| ADC_EN_SH_VRFEF        | 1      | O    | 0       |            | ADC_SEQ             |                 |
| ADC_EN_ALG             | 1      | O    | 0       |            | ADC_SEQ             |                 |
|                        |        |      |         |            |                     |                 |
| ADC_CMP_OUT_POS        | 1      | I    | N/A     |            | BIT_STREAM          |                 |
| ADC_CMP_OUT_NEG        | 1      | I    | N/A     |            | BIT_STREAM          |                 |
| ADC_CELL_CH_SEL        | 18     | O    | 0       |            | CH_SEL              |                 |
| ADC_GPIO_CH_SEL        | 12     | O    | 0       |            | CH_SEL              |                 |
| ADC_VPTAT_SEL          | 1      | O    | 0       |            | CH_SEL              |                 |
| ADC_VBG_SEL            | 1      | O    | 0       |            | CH_SEL              |                 |
| ADC_VBG2_SEL           | 1      | O    | 0       |            | CH_SEL              |                 |
| GPIO_REF_SEL           | 12     | O    | 0       |            | CH_SEL              |                 |
|                        |        |      |         |            |                     |                 |
| D2A_AUX_ADC_EN         | 1      | O    | 0       |            |                     |                 |
| AUX_ADC_CLK            | 1      | O    | 0       |            |                     |                 |
| AUX_ADC_CLK_H          | 1      | O    | 0       |            |                     |                 |
| AUX_ADC_POLAR          | 1      | O    | 0       |            | AUX_ADC_SEQ         |                 |
| AUX_ADC_RST_INT        | 1      | O    | 0       |            | AUX_ADC_SEQ         |                 |
| AUX_ADC_EN_SH_VIN      | 1      | O    | 0       |            | AUX_ADC_SEQ         |                 |
| AUX_ADC_EN_SH_VRFEF    | 1      | O    | 0       |            | AUX_ADC_SEQ         |                 |
| AUX_ADC_EN_ALG         | 1      | O    | 0       |            | AUX_ADC_SEQ         |                 |
|                        |        |      |         |            |                     |                 |
| AUX_ADC_CMP_OUT_POS    | 1      | I    | N/A     |            | AUX_BIT_STREAM      |                 |
| AUX_ADC_CMP_OUT_NEG    | 1      | I    | N/A     |            | AUX_BIT_STREAM      |                 |
| AUX_ADC_CELL_CH_SEL    | 18     | O    | 0       |            | AUX_CH_SEL          |                 |
| AUX_ADC_GPIO_CH_SEL    | 12     | O    | 0       |            | AUX_CH_SEL          |                 |
| AUX_ADC_VPTAT_SEL      | 1      | O    | 0       |            | AUX_CH_SEL          |                 |
| AUX_ADC_VBG_SEL        | 1      | O    | 0       |            | AUX_CH_SEL          |                 |
| AUX_ADC_VBG2_SEL       | 1      | O    | 0       |            | AUX_CH_SEL          |                 |
| AUX_GPIO_REF_SEL       | 12     | O    | 0       |            | AUX_CH_SEL          |                 |
|                        |        |      |         |            |                     |                 |
| TRIM                   | 256    | O    |         |            |                     |                 |
| SCAN_ EN               | 1      | I    |         |            | Scan related inputs | DFT             |
| SCAN_CLK               | 1      | I    |         |            | Scan related inputs | DFT             |
| SCAN_RSTB              | 1      | I    |         |            | Scan related inputs | DFT             |
| SCAN_MODE              | 1      | O    |         |            | Scan related inputs | DFT             |
| SCAN_IN1               | 1      | I    |         |            | Scan related inputs | DFT             |
| SCAN_IN2               | 1      | I    |         |            | Scan related inputs | DFT             |
| SCAN_IN3               | 1      | I    |         |            | Scan related inputs | DFT             |
| SCAN_IN4               | 1      | I    |         |            | Scan related inputs | DFT             |
| SCAN_OUT1              | 1      | O    |         |            | SCAN_OUTx           | DFT             |
| SCAN_OUT2              | 1      | O    |         |            | SCAN_OUTx           | DFT             |
| SCAN_OUT3              | 1      | O    |         |            | SCAN_OUTx           | DFT             |
| SCAN_OUT4              | 1      | O    |         |            | SCAN_OUTx           | DFT             |
|                        |        |      |         |            |                     |                 |
| ADR                    | 7      | O    |         |            |                     | for debug       |
| DIN                    | 8      | O    |         |            |                     | for debug       |
| CS                     | 1      | O    |         |            |                     | for debug       |
| READ                   | 1      | O    |         |            |                     | for debug       |
| WR                     | 1      | O    |         |            |                     | for debug       |
|                        |        |      |         |            |                     |                 |
| VD1RDY                 | 1      | I    |         |            | power source of MTP |                 |
| SUB                    | 1      | I    |         |            | ?                   |                 |
| VPP                    | 1      | I    |         |            | ?                   |                 |
| VDD1                   | 1      | I    |         |            | ?                   |                 |
| VDD2                   | 1      | I    |         |            | ?                   |                 |
| GND                    | 1      | I    |         |            | ?                   |                 |
| VDD_DIG                | 1      | I    |         |            | ?                   |                 |
| VSS_DIG                | 1      | I    |         |            | ?                   |                 |
|                        |        |      |         |            |                     |                 |
|                        |        |      |         |            |                     |                 |
|                        |        |      |         |            |                     |                 |
|                        |        |      |         |            |                     |                 |
|                        |        |      |         |            |                     |                 |

