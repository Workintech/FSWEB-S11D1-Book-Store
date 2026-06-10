# Gün Projesi: Book Store

Çalıştığın şirkette, deneyimli bir developer olarak anılacak kadar çalıştın. Şirkete alınan bir stajere de buddy oldun. İkinize bir Kitap alışveriş sitesi projesi verildi.

Beraber neler yapılacağını planladınız. Proje gittikçe büyüyecek ve çok fazla özellik ekelenecek. O, useState ile bir yere kadar getirecek sen de contextAPIye dönüştüreceksin.

Stajerin yaptığı halinde "Add to cart" çalışmasa da beklediğinden çok daha iyi şeyler yaptı.
Geriye kalanların listesi aşağıda, kalanları sen yapacaksın, o da seni izleyip öğrenecek.

- [ ] `src`altında `contexts` isinli bir klasör oluşturun ve içinde `ProductContext.jsx`dosyası oluştur.
- [ ] `createContect`i reacttan import et `ProductContext`i oluştur. Export etmeyi unutma.
- [ ] `ProductContext.Provider`ı return edecek bir fonksiyon oluştur. Adını `ProductContextProvider` yap. Export etmeyi unutma.
- [ ] İçinde products adıyla bir state oluştur. Bu statei ProductContext.Providera value olarak vermeyi unutma.
- [ ] `App.jsx`de uygulamanı bu provider ile sarmala.
- [ ] `App.jsx`de Products componentine gönderdiğin propları sil.
- [ ] `Products.jsx`de useContexti kullanarak ProductContext nesnesini bu hooka ver. prodcuts bilgisini al.

- [ ] `src/contexts` içinde `CartContext.jsx`dosyası oluştur.
- [ ] `createContect`i reacttan import et `CartContext`i oluştur. Export etmeyi unutma.
- [ ] `CartContext.Provider`ı return edecek bir fonksiyon oluştur. Adını `CartContextProvider` yap. Export etmeyi unutma.
- [ ] İçinde cart adıyla bir state oluştur.
- [ ] `addItem` metodunu burada oluştur.
- [ ] `removeItem`metodunu da oluştur.
- [ ] CartContext.Providera cart, addItem ve removeItemı value olarak vermeyi unutma.
- [ ] `App.jsx`de uygulamanı bu provider ile de sarmala.
- [ ] `App.jsx`de "Navigation" ve "ShoppingCart" componentine gönderdiğin propları sil.
- [ ] `Navigation.jsx`de useContexti kullanarak CartContext nesnesini bu hooka ver. cart bilgisini al.
- [ ] `ShoppingCart.jsx`de useContexti kullanarak CartContext nesnesini bu hooka ver. cart bilgisini al.
- [ ] `ShoppingCartItem.jsx`de useContexti kullanarak CartContext nesnesini bu hooka ver. removeItem fonksiyonu al ve kullan.
- [ ] `Products.jsx`de useContexti kullanarak CartContext nesnesini bu hooka ver. addItem bilgisini al.

- [ ] cart bilgilerini localStorageda `s11d1` anahtarı ile sakla. (src altında hook klasöründe içinde custom bir hook oluşturabilirsin.)
