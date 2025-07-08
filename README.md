<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Türkiye Gezi Rehberi - 15 Şehir</title>
<style>
  body { font-family: Arial, sans-serif; line-height: 1.6; margin: 0; padding: 0; background: #f4f7f9; color: #333; }
  h1, h2 { color: #064663; }
  .container { max-width: 1200px; margin: auto; padding: 20px; }
  .city-section { margin: 50px 0; padding: 20px; background: #fff; border-radius: 10px; box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1); }
  .city-section img { width: 100%; border-radius: 10px; max-height: 300px; object-fit: cover; }
  .place-list { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 20px; }
  .place-card { background: #fff; border-radius: 10px; box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1); overflow: hidden; }
  .place-card img { width: 100%; height: 160px; object-fit: cover; }
  .place-card div { padding: 15px; }
  .place-card h3 { color: #064663; margin-bottom: 10px; }
  .place-card p { font-size: 0.9rem; color: #555; }
  footer { text-align: center; padding: 20px; background: #042a2b; color: #fff; }
  .search { text-align: center; margin: 1rem; }
  .search input { width: 50%; padding: 0.5rem; font-size: 1rem; border-radius: 5px; border: 1px solid #ccc; }
</style>
</head>
<body>

<header class="container">
  <h1>Türkiye'nin En Güzel 15 Şehri</h1>
  <p>Tarihi, kültürel ve doğal güzellikleri keşfedin.</p>
</header>

<div class="search">
  <input type="text" id="search" placeholder="Şehir ara...">
</div>

<main class="container">

  <!-- İstanbul -->
  <section class="city-section" id="istanbul">
    <h2>İstanbul</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/8/8b/Hagia_Sophia_Mars_2013.jpg" alt="İstanbul">
    <p>Türkiye'nin en büyük ve tarihi açıdan en zengin şehri.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/19/Blue_Mosque.JPG" alt="Sultanahmet Camii">
        <div>
          <h3>Sultanahmet Camii</h3>
          <p>Mavi çinileriyle meşhur, tarihi camii.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f1/Grand_Bazaar_in_Istanbul.jpg" alt="Kapalıçarşı">
        <div>
          <h3>Kapalıçarşı</h3>
          <p>Dünyanın en eski ve büyük kapalı çarşısı.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/4c/Bosphorus_Bridge_at_night.jpg" alt="Boğaz Köprüsü">
        <div>
          <h3>Boğaz Köprüsü</h3>
          <p>Asya ve Avrupa'yı bağlayan ikonik köprü.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Ankara -->
  <section class="city-section" id="ankara">
    <h2>Ankara</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/7/7a/Ankara_Turkey_Skyline_2017.jpg" alt="Ankara">
    <p>Türkiye'nin başkenti ve modern şehir hayatının merkezi.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d0/Anitkabir_-_Ankara_-_Turkey_001.jpg" alt="Anıtkabir">
        <div>
          <h3>Anıtkabir</h3>
          <p>Mustafa Kemal Atatürk'ün anıt mezarı.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f6/Haci_Bayram_Mosque_-_Ankara_-_Turkey.JPG" alt="Hacı Bayram Camii">
        <div>
          <h3>Hacı Bayram Camii</h3>
          <p>16. yüzyıldan kalma tarihi camii ve türbe.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/62/Museum_of_Anatolian_Civilizations_Ankara_Turkey_02.jpg" alt="Anadolu Medeniyetleri Müzesi">
        <div>
          <h3>Anadolu Medeniyetleri Müzesi</h3>
          <p>Zengin arkeolojik koleksiyonlar sunar.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- İzmir -->
  <section class="city-section" id="izmir">
    <h2>İzmir</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Konak_Square%2C_Izmir%2C_Turkey.jpg" alt="İzmir">
    <p>Ege'nin incisi, güzel sahil şehirlerinden biri.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/63/Ephesus_Celsus_Library.jpg" alt="Efes Antik Kenti">
        <div>
          <h3>Efes Antik Kenti</h3>
          <p>Dünyaca ünlü antik Roma kenti.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/54/Kordonboyu_%C4%B0zmir.jpg" alt="Kordon Boyu">
        <div>
          <h3>Kordon Boyu</h3>
          <p>Popüler yürüyüş ve dinlenme alanı.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/7b/Agora_of_Smyrna.JPG" alt="Agora">
        <div>
          <h3>Agora</h3>
          <p>Antik Roma pazarı kalıntıları.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Bursa -->
  <section class="city-section" id="bursa">
    <h2>Bursa</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/9/90/Uluda%C4%9F_in_summer.jpg" alt="Bursa">
    <p>Yeşil Bursa, tarih ve doğa güzellikleriyle ünlü.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/40/Grand_Mosque_Bursa.jpg" alt="Ulu Camii">
        <div>
          <h3>Ulu Camii</h3>
          <p>Osmanlı mimarisinin önemli örneklerinden.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f7/Koza_Han%2C_Bursa.jpg" alt="Koza Han">
        <div>
          <h3>Koza Han</h3>
          <p>Tarihi ipek pazarı.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/2e/Uludag_Winter.jpg" alt="Uludağ">
        <div>
          <h3>Uludağ</h3>
          <p>Popüler kayak merkezi ve doğa harikası.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Antalya -->
  <section class="city-section" id="antalya">
    <h2>Antalya</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/4/4b/Antalya_D%C3%BCden_Waterfall.jpg" alt="Antalya">
    <p>Akdeniz'in incisi, tarihi ve doğal güzellikleriyle büyüler.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Aspendos_Amphitheatre.jpg" alt="Aspendos Tiyatrosu">
        <div>
          <h3>Aspendos Tiyatrosu</h3>
          <p>Antik tiyatronun en iyi korunmuş örneklerinden.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/e7/Antalya_Kalei%C3%A7i.jpg" alt="Kaleiçi">
        <div>
          <h3>Kaleiçi</h3>
          <p>Tarihi şehir merkezi, Osmanlı sokaklarıyla dolu.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/17/Duden_Falls_Antalya_2016.jpg" alt="Düden Şelalesi">
        <div>
          <h3>Düden Şelalesi</h3>
          <p>Doğa ile iç içe güzel bir şelale.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Konya -->
  <section class="city-section" id="konya">
    <h2>Konya</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Mevlana_Museum.JPG" alt="Konya">
    <p>Manevi atmosferi ve Selçuklu mirasıyla tanınır.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/2/26/Tropikal_Kelebek_Bah%C3%A7esi.jpg" alt="Tropikal Kelebek Bahçesi">
        <div>
          <h3>Tropikal Kelebek Bahçesi</h3>
          <p>Egzotik kelebeklerin bulunduğu doğal güzellik.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/4f/Alaaddin_hill.jpg" alt="Alaaddin Tepesi">
        <div>
          <h3>Alaaddin Tepesi</h3>
          <p>Selçuklu eserlerinin çevresinde yer alan tarihi tepe.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/e1/Semazen_Dervish.jpg" alt="Mevlana Müzesi">
        <div>
          <h3>Mevlana Müzesi</h3>
          <p>Mevlana Celaleddin Rumi'nin türbesi ve müzesi.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Trabzon -->
  <section class="city-section" id="trabzon">
    <h2>Trabzon</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/e3/Trabzon_Skyline.jpg" alt="Trabzon">
    <p>Karadeniz'in incisi, yeşil doğası ve tarihiyle bilinir.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/53/Sumela_Monastery_Trabzon.jpg" alt="Sümela Manastırı">
        <div>
          <h3>Sümela Manastırı</h3>
          <p>Kayalara oyulmuş tarihi manastır.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0a/Uzungol_Trabzon_Turkey.JPG" alt="Uzungöl">
        <div>
          <h3>Uzungöl</h3>
          <p>Doğa harikası göl ve çevresi.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/9/9d/Ataturk_Mansion_Trabzon.JPG" alt="Atatürk Köşkü">
        <div>
          <h3>Atatürk Köşkü</h3>
          <p>Atatürk’ün kullandığı tarihi köşk.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Edirne -->
  <section class="city-section" id="edirne">
    <h2>Edirne</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/2b/Edirne_Selimiye_Mosque_2.jpg" alt="Edirne">
    <p>Osmanlı mimarisinin önemli eserlerine ev sahipliği yapar.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/8d/Selimiye_Mosque_2016.jpg" alt="Selimiye Camii">
        <div>
          <h3>Selimiye Camii</h3>
          <p>Mimar Sinan'ın şaheserlerinden biri.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f8/Edirne_Old_Bazaar.JPG" alt="Edirne Eski Çarşı">
        <div>
          <h3>Edirne Eski Çarşı</h3>
          <p>Tarihi ve canlı pazar alanı.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0d/Meri%C3%A7_River_in_Edirne.jpg" alt="Meriç Nehri">
        <div>
          <h3>Meriç Nehri</h3>
          <p>Şehirden geçen önemli nehir.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Çanakkale -->
  <section class="city-section" id="canakkale">
    <h2>Çanakkale</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/f/f2/Çanakkale_Skyline_2014.jpg" alt="Çanakkale">
    <p>Tarihi Gelibolu Yarımadası ve Truva antik kenti ile bilinir.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/5b/Gelibolu_War_Cemetery_2008.jpg" alt="Gelibolu Yarımadası">
        <div>
          <h3>Gelibolu Yarımadası</h3>
          <p>Tarihi savaş alanları ve anıtlar.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/14/Troy_Antique_City_01.jpg" alt="Truva Antik Kenti">
        <div>
          <h3>Truva Antik Kenti</h3>
          <p>Tarihin efsanevi kenti.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d5/Çanakkale_Bridge_01.jpg" alt="Çanakkale Köprüsü">
        <div>
          <h3>Çanakkale Köprüsü</h3>
          <p>Asya ve Avrupa'yı bağlayan dev köprü.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Mardin -->
  <section class="city-section" id="mardin">
    <h2>Mardin</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/6e/Mardin_Sunset_2018.jpg" alt="Mardin">
    <p>Taş evleri ve tarihi dokusuyla Mezopotamya'nın incisi.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0b/Deyrulzafaran_Monastery_Mardin_Turkey_2013.jpg" alt="Deyrulzafaran Manastırı">
        <div>
          <h3>Deyrulzafaran Manastırı</h3>
          <p>Tarihi Süryani manastırı, kültürel zenginlik.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/45/Mardin_old_town.jpg" alt="Mardin Eski Şehir">
        <div>
          <h3>Mardin Eski Şehir</h3>
          <p>Dar sokakları, taş evleri ve panoramik manzarası.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a6/Zinciriye_Medresesi_Mardin_2014.jpg" alt="Zinciriye Medresesi">
        <div>
          <h3>Zinciriye Medresesi</h3>
          <p>Selçuklu döneminden kalma tarihi eğitim kurumu.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Gaziantep -->
  <section class="city-section" id="gaziantep">
    <h2>Gaziantep</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/31/Gaziantep_Town_Center.jpg" alt="Gaziantep">
    <p>Lezzetli yemekleri ve zengin tarihiyle ünlü şehir.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/7/7f/Gaziantep_Castle.JPG" alt="Gaziantep Kalesi">
        <div>
          <h3>Gaziantep Kalesi</h3>
          <p>Tarih boyunca önemli bir savunma noktası.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/c0/Gaziantep_Zoo_and_Botanical_Park.jpg" alt="Gaziantep Hayvanat Bahçesi">
        <div>
          <h3>Gaziantep Hayvanat Bahçesi</h3>
          <p>Doğa ve hayvan severler için güzel bir park.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6d/Zeugma_Mosaic_Museum.JPG" alt="Zeugma Mozaik Müzesi">
        <div>
          <h3>Zeugma Mozaik Müzesi</h3>
          <p>Dünyanın en büyük mozaik müzelerinden biri.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Kayseri -->
  <section class="city-section" id="kayseri">
    <h2>Kayseri</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/37/Kayseri_City_Center_2018.jpg" alt="Kayseri">
    <p>Tarihi ve doğal güzellikleriyle İç Anadolu'nun önemli şehri.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/e/e0/Kayseri_Castle_2017.JPG" alt="Kayseri Kalesi">
        <div>
          <h3>Kayseri Kalesi</h3>
          <p>Şehrin simgelerinden tarihi kale.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/c/c0/Erciyes_Mountain_Turkey_2015.JPG" alt="Erciyes Dağı">
        <div>
          <h3>Erciyes Dağı</h3>
          <p>Kış sporları için popüler bir dağ.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/8f/Gevenlik_Medresesi_Kayseri.jpg" alt="Gevenlik Medresesi">
        <div>
          <h3>Gevenlik Medresesi</h3>
          <p>Selçuklu mimarisinin güzel örneklerinden.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Adana -->
  <section class="city-section" id="adana">
    <h2>Adana</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/6/68/Adana_Skyline_2019.jpg" alt="Adana">
       <p>Lezzetli mutfağı ve tarihi yapılarıyla Akdeniz bölgesinin önemli kenti.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3f/Adana_Bridge_and_Beyazit_Mosque_2011.JPG" alt="Taşköprü">
        <div>
          <h3>Taşköprü</h3>
          <p>Roma döneminden kalma tarihi köprü.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/10/Adana_Sabanci_Merkez_Camii_2010.jpg" alt="Sabancı Merkez Camii">
        <div>
          <h3>Sabancı Merkez Camii</h3>
          <p>Türkiye'nin en büyük camilerinden biri.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/d/d6/Adana_Tasarim_Merkezi.jpg" alt="Atatürk Parkı">
        <div>
          <h3>Atatürk Parkı</h3>
          <p>Şehrin en büyük ve en yeşil parkı.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Samsun -->
  <section class="city-section" id="samsun">
    <h2>Samsun</h2>
    <img src="https://upload.wikimedia.org/wikipedia/commons/3/3c/Samsun_Skyline.jpg" alt="Samsun">
    <p>Kuzey Anadolu'nun önemli liman ve ticaret şehri.</p>
    <div class="place-list">
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/a/a1/Ataturk_Monument_Samsun.jpg" alt="Atatürk Anıtı">
        <div>
          <h3>Atatürk Anıtı</h3>
          <p>Milli mücadeleye ev sahipliği yapan simge anıt.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/53/Samsun_Archaeology_Museum.JPG" alt="Samsun Arkeoloji Müzesi">
        <div>
          <h3>Samsun Arkeoloji Müzesi</h3>
          <p>Zengin tarihi eser koleksiyonuna sahiptir.</p>
        </div>
      </div>
      <div class="place-card">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/06/Bandirma_City_Center_2020.jpg" alt="Bandırma">
        <div>
          <h3>Bandırma</h3>
          <p>Deniz kıyısında güzel bir tatil ve turizm merkezi.</p>
        </div>
      </div>
    </div>
  </section>

</main>

<footer>
  © 2025 Türkiye Gezi Rehberi | Tüm hakları saklıdır.
</footer>

<script>
  const searchInput = document.getElementById('search');
  searchInput.addEventListener('input', () => {
    const filter = searchInput.value.toLowerCase();
    document.querySelectorAll('.city-section').forEach(city => {
      const cityName = city.id.toLowerCase();
      city.style.display = cityName.includes(filter) ? 'block' : 'none';
    });
  });
</script>

</body>
</html>
