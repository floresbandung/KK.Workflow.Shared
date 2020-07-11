# KK.Workflow.Shared

# Activity Status
  - New

    Status New dibuat pada saat request baru dari satu proses
  - Approve
  
    Status approve dibuat jika user telah memberi approval dari satu activity
  - Partial Approve
  
    Status partial approve jika sebagian user memberi approval dari satu activity. Workflow engine akan melakukan pengecekan (>=) MinimumApprovalCount untuk menaikan ke activity selanjutnya.
  - Revise
  
    Mengembalikan activity ke status awal (New).
  - Reject
  
    Menutup/menolak (proses ke activity selanjutnya) dari satu proses tanpa menunggu sampai akhir activity
  - Closed

    Menutup satu proses yang sudah mencapai activity akhir (proses selesai).