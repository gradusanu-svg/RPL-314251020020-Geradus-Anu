# Logical View

```text
              +-----------+
              |  Pasien   |
              +-----------+
                    |
                    v
             +-------------+
             |    Login    |
             +-------------+
                    |
                    v
            +----------------+
            |   Dashboard    |
            +----------------+
          /       |        \
         /        |         \
        v         v          v
   Pendaftaran Rekam Medis Pembayaran
         \        |         /
          \       |        /
           \      |       /
               Database
```

## Penjelasan

Setelah login, pengguna dapat melakukan pendaftaran pasien, melihat rekam medis, melakukan pembayaran, dan seluruh data tersimpan pada database.
