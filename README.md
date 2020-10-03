# ESP32_LoRa_Transponder
Using a pair of ESP32 Lora Modules as a pair of transponders.

Example board: https://www.aliexpress.com/item/32998900007.html?spm=a2g0o.productlist.0.0.5635e39eYmdiRh&algo_pvid=0a7dc48e-cef0-457e-97c4-9cdbafd57469&algo_expid=0a7dc48e-cef0-457e-97c4-9cdbafd57469-19&btsid=0b0a187916017374115284728ec8c7&ws_ab_test=searchweb0_0,searchweb201602_,searchweb201603

Make sure your pin assignments match the suppliers pin-outs.

#define LoRA_SCK   5
#define LoRA_MISO 19
#define LoRA_MOSI 27
#define LoRA_CS   18
#define LoRA_RST  14
#define LoRA_IRQ  26

Match pins defined in yellow wioth programme definitions

![alt_text, width="200"](/ESP32_LORA.jpg)
