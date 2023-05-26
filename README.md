# ctaMTX Library
A Java library for converting PNG files into Mediocre's MTXv0 files.

Note: You may need to cut out the "0XTM" header manually after the image is converted.

------------------

# Support Me

[Support me here !](https://paypal.me/mattcampx)

------------------

## Example usage
```
    public static void main(String[] args) {

        try {

            convertToMtxv0("input.png", "output.mtx");

        } catch (IOException e) {

            e.printStackTrace();

        }

    }
```
