# Ex01 - Khởi dựng Sandbox Linux (WSL / VM)

## Cài đặt

**Windows (WSL 2):**
```powershell
wsl --install -d Ubuntu-24.04
```

**macOS:** cài UTM (Apple Silicon) hoặc VirtualBox/VMware (Intel), tạo VM từ ISO Ubuntu Server 24.04 LTS, sau đó SSH vào VM:
```bash
ssh <user>@<ip-vm>
```

## Kiểm tra

```bash
uname -a
cat /etc/os-release
```

Kết quả mong đợi: thông tin Ubuntu kèm phiên bản kernel.

## Nộp bài

Ảnh chụp terminal chạy `cat /etc/os-release`: [sandbox_setup.png](sandbox_setup.png)
