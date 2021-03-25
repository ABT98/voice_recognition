# voice_recognition
Uygulama wav dosylarını okuyarak cepstrum üretir(Hem eğitim hem test). 
Ardından Parametreleri eğitir, bu uygulamada az sözcük olduğundan oluşturulan matrste tahmin olmaz.
Yine veri az olduğundan dolayı kovaryans matrisler diagonaldir.

.wav dosyaları training_words ve testing_words'de bulunuyor. Testing'e trainingden farklı kelimeler ekleyerek doğruluğunu ölçüyoruz.
