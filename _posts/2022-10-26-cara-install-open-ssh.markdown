
<body>


<h2>SSH</h2>
<h3>apa itu ssh:</h3>
<p> SSH adalah sebuah protokol administrasi yang memungkinkan user untuk mengakses dan memodifikasi berbagai macam pengaturan maupun file yang ada di dalam server.
    Anda pernah mengenal Telnet? Nah, SSH merupakan pengembangan dari Telnet yang sebelumnya dianggap tidak aman karena tidak adanya proses enkripsi.
    Berbeda dengan Telnet, koneksi yang terjadi SSH dienkripsi menggunakan beberapa teknologi, seperti enkripsi simetris, enkripsi asimetris, dan hashing.</p>
    
    <h2>Cara Install Open SSH:</h2>
    <p>1. Sebelum Anda memulai instalasi OpenSSH, pertama-tama, buka terminal Ubuntu 22.04 dengan menekan “CTRL+ALT+T” dan konfirmasikan bahwa sistem Anda mutakhir</p>
    <img class="OpenSSH" src="https://previews.dropbox.com/p/thumb/ABu9x9t0roYrvB4oxtZimHZiCT0WQWhihZcDEQIFhwNBTYPNrWU1Uyt2yrxswvAKz5BbgqK3cxrS5OAUE1cFwctMsbUs-BVSHJgJBJf9XVQ2NtY3E73Ay1leOAhY-D2lgow9U2UqXsA42YnBKBZulAQ9faL1isfFuf_MI-7OmfgP2kZt_qCHpMsEqbLqbXvxDDhaFckTduYaPeJWMQz78R1_tylnkajFkRnK6entrgAEMTi-tLpcpgnO6EM3B_3Ki76q0pvG7RR_S7MpqmGizHsi0EanCeja165Xmnl7fue7Npp9JHvEaJLo5SBcs01p4OjTD6QSJ795LtmqZsCrdbEkA8N4htIZ0Epi8-9gOJZJzwUVPWpoBXtRF7NY_vWQe3c/p.png"><br>

    <p>2. OpenSSH tidak ada pada sistem secara default, oleh karena itu, jalankan perintah ini untuk memulai prosedur instalasi OpenSSH di Ubuntu 22.04</p>
    <img class="OpenSSH" src="https://previews.dropbox.com/p/thumb/ABvrzkak7zFP-UMrPhj2BM8w_KkPIkCKWeL9to5YkIe_HYgko3R0xEQT37jRU-f0Cng9cksR3SnwX2TxXpIjfAvlhzzE2BUo2y3c3_xDykxUhyufVOLJci-ps-IpaKPNDZ1BrkWEn0inXeGwyAs10DGXjbJknsxo81aMv94-drzJRpxq3k1skcIH4_7-kf66MtV4Of1xbMmSD3pY5a4z-21KEY6SIL2rJhg26DGq-1k3WNe5njjA6XVqlU-NrFWq3X5_aGXNilJRpFSHoJeC_pzpVRf34EC1bwG4qWzzpSLEKV0g_hDHHysoRUgjrSBP2qljdZ9FkBNzenMNvStEyKv2QloNol2Ly6GtEWkpsaJmpDoTIOtsPqOT9r3T6VPRRPk/p.png"><br>

    <p>3. Setelah instalasi OpenSSH berhasil, Anda harus mengaktifkannya di Ubuntu 22.04 dengan menggunakan perintah berikut:</p>
    <img class="OpenSSH" src="https://previews.dropbox.com/p/thumb/ABvaJDAmUGTPPG7vHYnYmSiltAteSlOtILG2k8BSGU3XQOsxydUZ8eu2QF3l-td9H5jd8Z7z9OZ-crDI0E7yYd3gOXZ2l2Mk99CVU1XCOkrZv1O4hVNqj94xXsMyGiyapNBthDAUf3ZzBiw_Kr3uvI9wwoVyG-8iDnWnirR3isOCPhVrgTE0MQcKhvnJ7LTlKT2z5jzAQ1stC608yeInzhdQwkTyLDg_DCmu7pc8A9X6c6DEUuGMd8soZrhn4LDoDucWwCXYZfwcuK5d69vMbo60rcj1DUdWHgCUWVEG_CoYenvIqXUdlLZnbnKInLxu7WfPYHvhBL-3JKxLQVVCEmc5FsMuqu1jHag7TrVlYqPXDrAR02DWfNCgwNUHL_jZxKk/p.png"><br>

    <P>4. Selanjutnya, validasi bahwa OpenSSH berfungsi dengan baik dan tidak ada masalah dengan bantuan perintah "systemctl" berikut:</P>
    <img class="OpenSSH" src="https://previews.dropbox.com/p/thumb/ABsyfANvuQ2eYLNwI4f1tJVBE5krwnH-3yKu4u-jrWskmFuZUzhbd2PHZ9b637xYoe3rW1i1IGiSSjtArVu-biXTqab4eANm6A52OrNAX1Nno7K50ax0BMMdtqwO8nAgCtYSDsZFS3hH7bBNytIsHMUecX9PuoR9QdS2Z3-kRHfIVNJgCmZ7nZ-cEuXuEio7DdZYI07bpPp5QQDwIgL0sLZ9DeJrUBOowSh-popzHOWLMZR7e5qydrsjzTFbZ67i7JUDU0t05-fACaOBCEOFa4OetqES8jEGwkDbka7irhEmsQ3Af5yuLdcnd1vWIHxTEVH0bFHoTqhQ1sIMhVCGi1PfUrif2ig1FKiv71KzcRdg8CNLw-VzlnP-Td2VWQp_qVc/p.png"><br>

    <p>5. Setelah Anda menginstal OpenSSH dan dalam keadaan berfungsi, Anda sekarang dapat menghubungkan sistem Anda ke sistem jarak jauh, komputer, atau server lain.</p>
    <img class="OpenSSH" src="https://previews.dropbox.com/p/thumb/ABvsaCGUNStz31yWXpN1JOWWyfLz8B7yRawOrBoof5H9I2r0HxdmOPvMxuuVnMSnjgVooPS6o0AiAyMxaOd9pz18Hg70yssJVnL9_GtMJlNspgPZLR8lZ2lKVfh0Ar3adMPM6z9glHDBRYjyOUKq_X9M9A92pkS9U3wK7u3fAXBQe3qnKkNtU65tqWBPpiZA-v1UIGAbiNDu6sIl9k2WfC7Wj_P1qr9j9R9_3KdRc4LUfNEP2vkKAY_I-7diwlNaifYywaDzQUzL2BF-vJIy_spRzSDDoFGkro__HwAJ9M5JXhdgFtci-d2rKq3GQsjGx5Zy3EOqHadrNr6GKuyFEXGDkFXQlV1RPPeks5T7yWXLzdIef-2Vm8yf4jwJgZc8kdA/p.png"><br>

</body>
        
<style>
body{
    background-image: linear-gradient(to right, rgba(255,0,0,0), rgba(255,0,0,1));
  
}
h2{
text-align: center;
}


</style>