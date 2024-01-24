import speedtest

def testar_velocidade_net():
    st = speedtest.Speedtest()
    
    print("testanto a velocidade...")

    download_speed = st.download() / 1_000_000
    upload_speed = st.upload() / 1_000_000
    ping = st.results.ping


    print(f"velocidade de download: {download_speed:.2f} mbps")
    print(f"velocidade de upload: {upload_speed:.2f} mbps")
    print(f"latencia.. {ping} ms")

if __name__ == "__main__":

    testar_velocidade_net()
