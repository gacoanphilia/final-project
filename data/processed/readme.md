| Variable | Class | Description |
| :--- | :--- | :--- |
| **year** | `int64` | Tahun musim kompetisi (Season Year) |
| **home_team** | `object` | Nama lengkap tim tuan rumah |
| **away_team** | `object` | Nama lengkap tim tamu |
| **winner** | `object` | Pemenang pertandingan |
| **tie** | `object` | Indikator hasil seri (jika seri, berisi nama tim yang dianggap 'losing') |
| **day** | `object` | Hari pertandingan (e.g., Sun, Mon, Thu) |
| **date** | `datetime64[ns]` | Tanggal pertandingan |
| **time** | `object` | Jam mulai pertandingan (lokal) |
| **pts_win** | `int64` | Poin yang dicetak oleh tim pemenang |
| **pts_loss** | `int64` | Poin yang dicetak oleh tim yang kalah |
| **yds_win** | `int64` | Total yards yang diraih tim pemenang |
| **turnovers_win** | `int64` | Jumlah turnover (kesalahan) tim pemenang |
| **yds_loss** | `int64` | Total yards yang diraih tim yang kalah |
| **turnovers_loss** | `int64` | Jumlah turnover (kesalahan) tim yang kalah |
| **home_team_name** | `object` | Nama julukan tim tuan rumah (e.g., Cowboys) |
| **home_team_city** | `object` | Kota asal tim tuan rumah |
| **away_team_name** | `object` | Nama julukan tim tamu |
| **away_team_city** | `object` | Kota asal tim tamu |
| **kickoff_time** | `datetime64[ns]` | Waktu kickoff lengkap (gabungan date & time) |
| **week_num** | `int64` | Nomor minggu pertandingan (1-17) |
| **total** | `int64` | Total kehadiran penonton akumulatif satu musim |
| **home** | `int64` | Total kehadiran penonton di kandang satu musim |
| **away** | `int64` | Total kehadiran penonton tandang satu musim |
| **attendance** | `int64` | **Jumlah penonton pada pertandingan tersebut (Weekly)** |
| **wins** | `int64` | Total kemenangan tim tuan rumah musim itu |
| **loss** | `int64` | Total kekalahan tim tuan rumah musim itu |
| **points_for** | `int64` | Total poin dicetak (Offense) tim tuan rumah per musim |
| **points_against** | `int64` | Total kebobolan (Defense) tim tuan rumah per musim |
| **points_differential**| `int64` | Selisih poin (`points_for` - `points_against`) |
| **margin_of_victory** | `float64` | Rata-rata margin kemenangan (SRS metric) |
| **strength_of_schedule**| `float64` | Tingkat kesulitan jadwal lawan (SRS metric) |
| **simple_rating** | `float64` | **Simple Rating System (SRS)**: Rating kualitas tim keseluruhan |
| **offensive_ranking** | `float64` | **Offensive SRS**: Rating kekuatan serangan tim |
| **defensive_ranking** | `float64` | **Defensive SRS**: Rating kekuatan pertahanan tim |
| **playoffs** | `object` | Status playoff tim tuan rumah (Playoffs/No Playoffs) |
| **sb_winner** | `object` | Status juara Superbowl (Won Superbowl/No Superbowl) |
| **home_score_diff** | `int64` | Margin skor tuan rumah pada game tersebut (+ Menang, - Kalah) |