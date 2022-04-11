# Metot-Tan-mlama
// METOT TANIMLAMA
            // Metotları programı küçük parçalara ayrıştırmak için kullanırız.Büyük bir ii tek bir metot içinde yazmak yerine küçük parçalara ayırarak yazmak daha doğru bir yaklaşımdır.
            //Bu bizi hem kod tekrarından kurtarır hem de daha okunabilir kod parçaları yazmamızı sağlar.
            //Metot=Fonksiyon.
            //Metodun bir class içinde yazılması gerekiyor.
            // erişim_belirteci geri_dönüştipi metot_adi (parametreListesi/argüman)
            //{
            /// KOMUTLAR;
            /// return;
            /// {
            int a = 2;
            int b = 3;
            Console.WriteLine(a + b);
            Topla(a, b);
            int sonuc = Topla(a, b);
            Console.WriteLine(sonuc);







            Console.ReadLine();

        }
        static  int  Topla(int deger1, int deger2)
        {
            return(deger1 + deger2);    

        }
    }
}
