[English below]
## Xin chào !!!

## Đầu tiên, nếu bạn không có account, hãy giúp mình 1 ref nhé. Link ủng hộ mình: [Click](https://app.nodepay.ai/register?ref=sRzFlYyB83Z7M3s), động lực to lớn để mình tiếp tục share và fix tool cho mọi người nhé

## Cách chạy Nodepay
1. Install Python 3.12. Bạn có thể lên youtube để tìm cách cài nhé.
2. Lấy data Nodepay của bạn.
   
   2.1 Để lấy token, bạn vào dashboard của bạn bằng link [here](https://app.nodepay.ai/dashboard) và nhấn phím F12, mở dev tool của trình duyệt.

   2.2 Chuyển qua tab Console => Bạn gõ lệnh
   ```bash
   localStorage.getItem('np_token')
   ```
   Copy token và dán vào trong file data.txt
4. Nếu bạn có proxy thì dán proxy của bạn theo cấu trúc http://user:password@ip:port. Bạn có bao nhiêu proxy thì thêm bấy nhiêu dòng token trong file data.txt nhé!!
5. Tải source code này về
6. Trong dev tool, bạn chuyển qua tab Network, tìm api session. Copy giá trị cookie ở dưới request header
7. Mở file nodepay.py, dòng 72 và paste value vào cookie
8. Mở terminal, `cd` vào thư mục chứa code của bạn
9. Tải package: Gõ lệnh
   ```bash
   pip install -r requirements.txt
   ```
10. Chạy nodepay
   ```bash
   py nodepay.py
   ```

## Ủng hộ mình ly cà phê bạn có thể chuyển qua momo cho mình.
![Donate](https://github.com/hthodev/nodepay/blob/main/momo_donate_me.jpg?raw=true)

## Welcome!!!!

## If you don't have account, [Click](https://app.nodepay.ai/register?ref=sRzFlYyB83Z7M3s) to registry support 1 ref for me.

## How to use GRASS
1. Install python 3.12
2. Put data into data.txt(token) and proxy.txt(http://username:password@ip:port)
   To get token. Go to [here](https://app.getgrass.io/dashboard). Press F12, open dev tools. Click tab console.
   ```bash
   localStorage.getItem('np_token')
   ```
3. Put proxy if you have.
4. Download source code
5. Open dev tool, click tab Network, Copy value cookie on api session
6. Open file nodepay.py, edit Cookie on line 72.
7. Open terminal, `cd` your source code
8. Install package
    ```bash
    pip install -r requirements.txt
    ```
9. Start code
   ```bash
   py nodepay.py
   ```

## Thanks to all contributors ❤
