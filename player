<!-- British Vintage Cafe Theme Music Player (Fixed Logic) -->
<div style="
    width:360px; 
    padding:25px; 
    border-radius:18px; 
    background:#F2E8D5; 
    box-shadow:0 5px 15px rgba(0,0,0,0.15); 
    font-family:Georgia, serif;
    border:3px solid #7A3E2C;
">

    <!-- Music Title -->
    <div style="font-weight:bold; font-size:22px; margin-bottom:15px; color:#1F3A60;">
        🎵 The Red Brick Café
    </div>

    <!-- Hidden YouTube iframe -->
    <div style="display:none;">
        <iframe id="ytplayer" width="0" height="0"
            src="https://www.youtube.com/embed/RCmj8NQwgbo?si=3LHMeD0PdQ5KDtiP&controls=0"
            frameborder="0" allow="autoplay"></iframe>
    </div>

    <!-- Controls Row -->
    <div style="display:flex; gap:12px;">

        <!-- Play Button -->
        <button onclick="playCafeMusic()"
            style="
                flex:1;
                padding:12px 0; 
                border:0; 
                border-radius:30px; 
                background:#1F3A60; 
                color:#F2E8D5; 
                cursor:pointer;
                font-size:16px;
                font-weight:bold;
                box-shadow:0 3px 6px rgba(0,0,0,0.2);
            ">
            ▶ Play
        </button>

        <!-- Stop Button -->
        <button onclick="stopCafeMusic()"
            style="
                flex:1;
                padding:12px 0; 
                border:0; 
                border-radius:30px; 
                background:#7A3E2C; 
                color:#F2E8D5; 
                cursor:pointer;
                font-size:16px;
                font-weight:bold;
                box-shadow:0 3px 6px rgba(0,0,0,0.2);
            ">
            ⏸ Stop
        </button>
    </div>
</div>

<script>
  // 기본 유튜브 URL (autoplay 파라미터 없이)
  const YT_BASE_URL = "https://www.youtube.com/embed/RCmj8NQwgbo?si=3LHMeD0PdQ5KDtiP&controls=0";

  function playCafeMusic() {
    const iframe = document.getElementById('ytplayer');
    // 항상 같은 기본 URL + autoplay=1
    iframe.src = YT_BASE_URL + "&autoplay=1";
  }

  function stopCafeMusic() {
    const iframe = document.getElementById('ytplayer');
    // 재생 멈출 때는 그냥 기본 URL로만 돌려놓기 (또는 빈 값도 가능)
    iframe.src = YT_BASE_URL;
  }
</script>
