CC=dtc
CFLAGS=-@ --symbols -I dts -O dtb -o
SOURCE=i2c-st25dv-overlay.dts
TARGET=i2c-st25dv.dtbo

all: $(TARGET)

i2c-st25dv.dtbo: $(SOURCE)
	$(CC) $(CFLAGS) $(TARGET) $(SOURCE)

clean:
	rm -rf $(TARGET)

