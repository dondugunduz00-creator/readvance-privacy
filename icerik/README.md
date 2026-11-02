# ReadVance içerik paketleri

Uygulama güncellemesi gerektirmeden yeni okuma parçaları buradan dağıtılır.
`index.json` paket listesidir; her paket kendi klasöründe `pack.json` ve ses dosyalarıyla durur.
Paketler `ReadVance-kaynak` deposundaki `tools/make_pack.py` ile üretilir; elle düzenlenmemelidir.
Her dosya SHA-256 özetiyle doğrulanır; bozuk ya da eksik paket uygulama tarafından reddedilir.
