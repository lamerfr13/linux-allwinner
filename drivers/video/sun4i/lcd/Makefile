obj-$(CONFIG_LYCHEE_LCD_SUN4I) += lcd.o

lcd-objs := dev_lcd.o
ifeq ($(CONFIG_LYCHEE_LCD_MID9742),y)
	lcd-objs += lcd_bak/mid9742.o
else
ifeq ($(CONFIG_LYCHEE_LCD_AINOL_AUROTA),y)
	lcd-objs += lcd_bak/ainol_aurota.o
else
	lcd-objs += lcd0_panel_cfg.o
endif
endif
lcd-objs += lcd1_panel_cfg.o
