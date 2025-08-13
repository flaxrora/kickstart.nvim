# Neovim Konfigürasyonu - Klavye Kısayolları (Doğrulanmış)

Bu dokuman, mevcut Neovim konfigürasyonundaki **gerçekte çalışan** tüm klavye kısayollarını ve kullanımlarını açıklar.

## Leader Key
- **Leader Key**: `,` (virgül)
- **Local Leader Key**: `,` (virgül)

## Temel Navigasyon

### Window (Pencere) Yönetimi
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `<C-h>` | Sol pencereye geç | Ctrl + h |
| `<C-j>` | Alt pencereye geç | Ctrl + j |
| `<C-k>` | Üst pencereye geç | Ctrl + k |
| `<C-l>` | Sağ pencereye geç | Ctrl + l |
| `\|` | Dikey split aç | Pipe/Boru işareti (Shift + \) |
| `_` | Yatay split aç (karmaşık komut) | Alt çizgi (Shift + -) |

### Buffer ve Tab Yönetimi
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `,,` | Son buffer'a geç | Virgül + Virgül (iki kez virgül) |
| `tt` | Yeni tab aç | t + t (iki kez t harfi) |
| `[t` / `t[` | Önceki tab | [ + t VEYA t + [ |
| `]t` / `t]` | Sonraki tab | ] + t VEYA t + ] |
| `[T` | İlk tab | [ + Shift+T |
| `]T` | Son tab | ] + Shift+T |

### Quickfix Navigation
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `]f` | Sonraki quickfix | ] + f |
| `[f` | Önceki quickfix | [ + f |
| `,qo` | Quickfix aç | Virgül + q + o |
| `,qc` | Quickfix kapat | Virgül + q + c |
| `,qn` | Sonraki quickfix | Virgül + q + n |
| `,qp` | Önceki quickfix | Virgül + q + p |

## Editor Komutları

### Genel
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `jj` | Insert mode'dan çık (Escape) | j + j (iki kez j harfi) |
| `;` | Komut satırını aç (:) | Noktalı virgül |
| `<Enter>` | Yeni satır aç (normal mode'da) | Enter tuşu |
| `<Space>` | Boşluk ekle | Space/Boşluk tuşu |
| `<Esc>` | Arama vurgulamasını kapat | Escape tuşu |
| `, ` | Arama vurgulamasını kapat | Virgül + Boşluk |

### Diagnostics
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `[q` | Önceki diagnostic mesaj | [ + q |
| `]q` | Sonraki diagnostic mesaj | ] + q |
| `,d` | Diagnostic float window | Virgül + d |
| `,q` | Diagnostic quickfix list | Virgül + q |

### Text Yönlendirme
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `k` | Yukarı (word wrap destekli) | k harfi |
| `j` | Aşağı (word wrap destekli) | j harfi |

## Plugin Kısayolları

### Telescope (Fuzzy Finder)
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `,sf` | Dosya ara | Virgül + s + f |
| `,sh` | Yardım etiketlerinde ara | Virgül + s + h |
| `,sk` | Keymaps ara | Virgül + s + k |
| `,sw` | Mevcut kelimeyi ara | Virgül + s + w |
| `,sg` | Live grep ile ara | Virgül + s + g |
| `,sd` | Diagnostics ara | Virgül + s + d |
| `,sr` | Telescope resume | Virgül + s + r |
| `,ss` | Telescope builtin seçenekleri | Virgül + s + s |
| `,s.` | Son açılan dosyalar | Virgül + s + . (nokta) |
| `,s/` | Açık dosyalarda ara | Virgül + s + / (slash) |
| `,sn` | Neovim config dosyalarında ara | Virgül + s + n |
| `,?` | Son açılan dosyalar | Virgül + ? |
| `,b` | Buffer'lar | Virgül + b |
| `,,` | Buffer'lar | Virgül + Virgül |
| `,/` | Mevcut buffer'da fuzzy search | Virgül + / (slash) |
| `<C-t>` | Git dosyaları | Ctrl + t |
| `,gs` | Git status | Virgül + g + s |

### LSP (Language Server Protocol)
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `,rn` | Yeniden adlandır | Virgül + r + n |
| `,w` | Code action | Virgül + w |
| `gd` | Tanıma git | g + d |
| `gr` | Referansları göster | g + r |
| `gI` | Implementation'a git | g + Shift+I |
| `,D` | Type definition | Virgül + Shift+D |
| `K` | Hover documentation | Shift+K |
| `gD` | Declaration'a git | g + Shift+D |
| `,wa` | Workspace folder ekle | Virgül + w + a |
| `,wr` | Workspace folder kaldır | Virgül + w + r |
| `,wl` | Workspace folder'ları listele | Virgül + w + l |

### LSP Saga
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `,lo` | LSP outline | Virgül + l + o |
| `,lf` | LSP finder | Virgül + l + f |

### Git (Gitsigns & Fugitive)
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `[c` | Önceki git hunk | [ + c |
| `]c` | Sonraki git hunk | ] + c |
| `,ph` | Hunk önizleme | Virgül + p + h |
| `,gv` | Hunk seç | Virgül + g + v |
| `,gg` | Git Fugitive dikey aç | Virgül + g + g |
| `,gb` | Git Fugitive buffer'da aç | Virgül + g + b |

### Neo-tree (File Explorer)
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `,kk` | Neo-tree toggle (float) | Virgül + k + k |
| `,kc` | Neo-tree current position | Virgül + k + c |
| `,kb` | Neo-tree toggle (sol tarafta) | Virgül + k + b |
| `,kq` | Neo-tree kapat | Virgül + k + q |

### Terminal (ToggleTerm)
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `,tt` | Terminal toggle (float) | Virgül + t + t |
| `,tr` | Terminal sağda aç | Virgül + t + r |
| `,tb` | Terminal altta aç | Virgül + t + b |
| `jj` | Terminal mode'dan çık | j + j (iki kez j harfi) |
| `<Esc><Esc>` | Terminal mode'dan çık | Escape + Escape (iki kez) |

### Hop (Easy Motion)
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `<C-e>` | Kelime hop | Ctrl + e |

### Trouble (Diagnostics)
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `,xx` | Trouble window göster | Virgül + x + x |
| `,xw` | Workspace diagnostics | Virgül + x + w |
| `,xd` | Document diagnostics | Virgül + x + d |
| `,xq` | Quickfix list | Virgül + x + q |
| `,xl` | Location list | Virgül + x + l |
| `gR` | LSP references (Trouble ile) | g + Shift+R |

### Refactoring
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `,rr` | Refactoring seçenekleri | Virgül + r + r |

### Neogen (Documentation Generator)
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `,nf` | Dokümantasyon generate et | Virgül + n + f |

## Özel Konfigürasyon
| Kısayol | Açıklama | Nasıl Basılır |
|---------|----------|---------------|
| `,ev` | Neovim config dosyasını aç | Virgül + e + v |
| `,ed` | Dotfiles install script'ini aç | Virgül + e + d |

## Which-Key Grupları
Bu konfigürasyon which-key eklentisi kullanıyor ve aşağıdaki grup tanımlamaları mevcut:
- `,s` - **[S]earch** (Arama işlemleri)
- `,t` - **[T]oggle** (Toggle işlemleri)

## Blink.cmp (Autocompletion)
Otomatik tamamlama için varsayılan klavye kısayolları:
- `<C-y>` - Tamamlamayı kabul et

## Terminal Mode Özel Kısayollar
- `jj` - Terminal mode'dan normal mode'a geç
- `<Esc><Esc>` - Terminal mode'dan normal mode'a geç

## Notlar
- **DOĞRULANDI**: Bu kısayollar kaynak koddan doğrudan çıkarılmıştır
- Konfigürasyon `kickstart.nvim` tabanlı
- `phoenix` özel modülü ek özellikler sağlıyor
- Çoğu eklenti lazy loading kullanıyor
- Which-key eklentisi aktif kısayolları göstermek için kullanılıyor
- Leader key `,` (virgül) olarak ayarlanmış (standart `<Space>` değil)

Bu kısayollar, modern Neovim geliştirme ortamı için optimize edilmiştir ve LSP, Telescope, ve diğer popüler eklentilerle entegre çalışır.
