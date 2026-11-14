<!-- README.md -->

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 320" width="900" height="320" shape-rendering="crispEdges" xmlns:c2pa="http://c2pa.org/manifest">
  <defs>
    <linearGradient id="bg" x1="0" y1="0" x2="0" y2="1">
      <stop offset="0" stop-color="#0b0f1a"/>
      <stop offset="1" stop-color="#1a1f3d"/>
    </linearGradient>
    <clipPath id="typeclip">
      <rect x="250" y="178" width="0" height="30">
        <animate attributeName="width" values="0;420;420;0" keyTimes="0;0.45;0.9;1" dur="8s" repeatCount="indefinite"/>
      </rect>
    </clipPath>
  </defs>

  <rect width="900" height="320" fill="url(#bg)"/>

  <!-- twinkling stars -->
  <g fill="#ffffff">
    <rect x="40" y="30" width="4" height="4"><animate attributeName="opacity" values="1;0.1;1" dur="2s" repeatCount="indefinite"/></rect>
    <rect x="130" y="70" width="4" height="4"><animate attributeName="opacity" values="0.2;1;0.2" dur="3s" repeatCount="indefinite"/></rect>
    <rect x="300" y="24" width="4" height="4"><animate attributeName="opacity" values="1;0.1;1" dur="2.5s" repeatCount="indefinite"/></rect>
    <rect x="460" y="50" width="4" height="4"><animate attributeName="opacity" values="0.1;1;0.1" dur="1.8s" repeatCount="indefinite"/></rect>
    <rect x="600" y="28" width="4" height="4"><animate attributeName="opacity" values="1;0.2;1" dur="3.2s" repeatCount="indefinite"/></rect>
    <rect x="760" y="64" width="4" height="4"><animate attributeName="opacity" values="0.2;1;0.2" dur="2.2s" repeatCount="indefinite"/></rect>
    <rect x="860" y="30" width="4" height="4"><animate attributeName="opacity" values="1;0.1;1" dur="2.8s" repeatCount="indefinite"/></rect>
    <rect x="560" y="90" width="4" height="4"><animate attributeName="opacity" values="0.3;1;0.3" dur="1.6s" repeatCount="indefinite"/></rect>
  </g>

  <!-- ===== PIXEL LAPTOP ===== -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-6;0,0" dur="3s" repeatCount="indefinite"/>
    <!-- screen frame -->
    <rect x="60" y="120" width="160" height="108" fill="#8892b0"/>
    <rect x="64" y="124" width="152" height="100" fill="#2d3250"/>
    <rect x="72" y="132" width="136" height="84" fill="#0b0f1a"/>
    <!-- window dots -->
    <rect x="78" y="137" width="6" height="6" fill="#ff5f56"/>
    <rect x="88" y="137" width="6" height="6" fill="#ffbd2e"/>
    <rect x="98" y="137" width="6" height="6" fill="#27c93f"/>
    <!-- code lines (typing) -->
    <rect x="80" y="150" width="0" height="6" fill="#4cc9f0"><animate attributeName="width" values="0;70;70;0" keyTimes="0;0.2;0.9;1" dur="6s" begin="0s" repeatCount="indefinite"/></rect>
    <rect x="92" y="161" width="0" height="6" fill="#f72585"><animate attributeName="width" values="0;54;54;0" keyTimes="0;0.2;0.9;1" dur="6s" begin="0.5s" repeatCount="indefinite"/></rect>
    <rect x="92" y="172" width="0" height="6" fill="#ffd166"><animate attributeName="width" values="0;86;86;0" keyTimes="0;0.2;0.9;1" dur="6s" begin="1s" repeatCount="indefinite"/></rect>
    <rect x="92" y="183" width="0" height="6" fill="#06d6a0"><animate attributeName="width" values="0;40;40;0" keyTimes="0;0.2;0.9;1" dur="6s" begin="1.5s" repeatCount="indefinite"/></rect>
    <rect x="80" y="194" width="0" height="6" fill="#4cc9f0"><animate attributeName="width" values="0;24;24;0" keyTimes="0;0.2;0.9;1" dur="6s" begin="2s" repeatCount="indefinite"/></rect>
    <!-- cursor -->
    <rect x="80" y="205" width="6" height="8" fill="#ffffff"><animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/></rect>
    <!-- base -->
    <rect x="44" y="228" width="192" height="12" fill="#8892b0"/>
    <rect x="100" y="228" width="80" height="4" fill="#5c6784"/>
    <rect x="52" y="240" width="176" height="4" fill="#5c6784"/>
  </g>

  <!-- ===== PIXEL CAMERA ===== -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-6;0,0" dur="3s" begin="1.5s" repeatCount="indefinite"/>
    <!-- top bump + shutter -->
    <rect x="700" y="124" width="52" height="16" fill="#3a4170"/>
    <rect x="812" y="128" width="20" height="12" fill="#f72585"/>
    <!-- flash -->
    <rect x="770" y="128" width="24" height="12" fill="#ffd166">
      <animate attributeName="opacity" values="1;1;0.15;1;1" keyTimes="0;0.7;0.78;0.86;1" dur="3s" repeatCount="indefinite"/>
    </rect>
    <!-- body -->
    <rect x="676" y="140" width="176" height="104" fill="#2d3250"/>
    <rect x="676" y="140" width="176" height="8" fill="#3a4170"/>
    <rect x="676" y="212" width="176" height="32" fill="#1d2140"/>
    <!-- lens -->
    <rect x="728" y="158" width="72" height="72" fill="#0b0f1a"/>
    <rect x="736" y="166" width="56" height="56" fill="#3a86ff"/>
    <rect x="744" y="174" width="40" height="40" fill="#1d3a8a"/>
    <rect x="752" y="182" width="24" height="24" fill="#0b0f1a"/>
    <rect x="756" y="186" width="8" height="8" fill="#ffffff">
      <animate attributeName="opacity" values="1;0.3;1" dur="2s" repeatCount="indefinite"/>
    </rect>
    <!-- rec light -->
    <rect x="690" y="156" width="10" height="10" fill="#ff3b3b">
      <animate attributeName="opacity" values="1;0;1" dur="1.2s" repeatCount="indefinite"/>
    </rect>
  </g>

  <!-- flash sparkles near camera -->
  <g fill="#ffd166">
    <rect x="800" y="104" width="6" height="6"><animate attributeName="opacity" values="0;0;1;0" keyTimes="0;0.7;0.8;1" dur="3s" repeatCount="indefinite"/></rect>
    <rect x="816" y="92" width="4" height="4"><animate attributeName="opacity" values="0;0;1;0" keyTimes="0;0.72;0.82;1" dur="3s" repeatCount="indefinite"/></rect>
    <rect x="786" y="92" width="4" height="4"><animate attributeName="opacity" values="0;0;1;0" keyTimes="0;0.74;0.84;1" dur="3s" repeatCount="indefinite"/></rect>
  </g>

  <!-- ===== TEXT ===== -->
  <g font-family="'Courier New', Courier, monospace" text-anchor="middle">
    <text x="450" y="104" font-size="26" font-weight="bold" fill="#ffffff">MIGUEL TERENCE JARIN</text>
    <text x="450" y="104" font-size="26" font-weight="bold" fill="#4cc9f0" opacity="0.35" dx="2" dy="2">MIGUEL TERENCE JARIN</text>
    <text x="450" y="140" font-size="15" fill="#06d6a0">&lt;/&gt; yeyensmoves</text>
    <text x="450" y="168" font-size="14" fill="#ffd166">Frontend Dev • Video Editor • Creative Tech</text>
    <g clip-path="url(#typeclip)">
      <text x="450" y="198" font-size="13" fill="#c9d1d9">Turning ideas into digital experiences &amp; visual stories.</text>
    </g>
  </g>

  <!-- ===== PIXEL GROUND ===== -->
  <g fill="#2d3250">
    <rect x="0" y="272" width="900" height="8"/>
  </g>
  <g fill="#3a4170">
    <rect x="0" y="280" width="900" height="40"/>
  </g>
  <g fill="#4cc9f0">
    <rect x="0" y="272" width="900" height="2" opacity="0.6"/>
  </g>
  <!-- running pixel dot -->
  <rect x="0" y="262" width="10" height="10" fill="#f72585">
    <animate attributeName="x" values="-20;910" dur="7s" repeatCount="indefinite"/>
  </rect>
  <rect x="0" y="254" width="10" height="8" fill="#ffd166">
    <animate attributeName="x" values="-20;910" dur="7s" repeatCount="indefinite"/>
  </rect>
<metadata><c2pa:manifest>AAAWgmp1bWIAAAAeanVtZGMycGEAEQAQgAAAqgA4m3EDYzJwYQAAABZcanVtYgAAAEdqdW1kYzJtYQARABCAAACqADibcQN1cm46YzJwYTowZGE0Y2VlYS0yNGE4LTQ1NGMtOGJlOC0xNTk2MGMxNDI4MDYAAAADl2p1bWIAAAApanVtZGMyYXMAEQAQgAAAqgA4m3EDYzJwYS5hc3NlcnRpb25zAAAAALxqdW1iAAAARGp1bWRjYm9yABEAEIAAAKoAOJtxE2MycGEuaW5ncmVkaWVudC52MwAAAAAYYzJzaDBj7eNvOIZbKDUcLB/2UWQAAABwY2JvcqNpZGM6Zm9ybWF0bWltYWdlL3N2Zyt4bWxqaW5zdGFuY2VJRHgseG1wOmlpZDpkNmQ4MWM4OC0yOWQ5LTQxODUtODhkYy0xYjE2ZTBkNWVjYTBscmVsYXRpb25zaGlwaHBhcmVudE9mAAAB4mp1bWIAAABBanVtZGNib3IAEQAQgAAAqgA4m3ETYzJwYS5hY3Rpb25zLnYyAAAAABhjMnNoEy0UdkKKeheq2FOv4yfWcAAAAZljYm9yomdhY3Rpb25zgqJmYWN0aW9ua2MycGEub3BlbmVkanBhcmFtZXRlcnOha2luZ3JlZGllbnRzgaJjdXJseC1zZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmluZ3JlZGllbnQudjNkaGFzaFgga1fCALeaToeKvVkRTUMvF49U4nMj0YceJ2p66hTMD2akZmFjdGlvbngdY29tLmFudGhyb3BpYy5jbGF1ZGUucHJvdmlkZWRqcGFyYW1ldGVyc6F4H2NvbS5hbnRocm9waWMub3JpZ2luLWNvbmZpZGVuY2VndW5rbm93bmtkZXNjcmlwdGlvbnhmQ2xhdWRlIHByb3ZpZGVkIHRoaXMgZmlsZSBhdCB0aGUgcmVxdWVzdCBvZiBhIHVzZXIgYW5kIG1heSBoYXZlIGNyZWF0ZWQgb3IgbW9kaWZpZWQgdGhlIGZpbGUgY29udGVudHMubXNvZnR3YXJlQWdlbnShZG5hbWVmQ2xhdWRlcmFsbEFjdGlvbnNJbmNsdWRlZPUAAADIanVtYgAAAEBqdW1kY2JvcgARABCAAACqADibcRNjMnBhLmhhc2guZGF0YQAAAAAYYzJzaLpPPDFnvUTfZNbHCkFu2H8AAACAY2JvcqVjYWxnZnNoYTI1NmNwYWRMAAAAAAAAAAAAAAAAZGhhc2hYIPgDt8mYzfi0qKAWA6I8b9Mz4XY4XMgLFvq6AX2D9rKFZG5hbWVuanVtYmYgbWFuaWZlc3RqZXhjbHVzaW9uc4GiZXN0YXJ0GRvkZmxlbmd0aBkeBAAAAj5qdW1iAAAAJ2p1bWRjMmNsABEAEIAAAKoAOJtxA2MycGEuY2xhaW0udjIAAAACD2Nib3KlY2FsZ2ZzaGEyNTZpc2lnbmF0dXJleE1zZWxmI2p1bWJmPS9jMnBhL3VybjpjMnBhOjBkYTRjZWVhLTI0YTgtNDU0Yy04YmU4LTE1OTYwYzE0MjgwNi9jMnBhLnNpZ25hdHVyZWppbnN0YW5jZUlEeCx4bXA6aWlkOjhkNDJkM2I0LTY3MjUtNGNlNi1hYmUzLTg5ZTkyOGFhOGFhN3JjcmVhdGVkX2Fzc2VydGlvbnODomN1cmx4LXNlbGYjanVtYmY9YzJwYS5hc3NlcnRpb25zL2MycGEuaW5ncmVkaWVudC52M2RoYXNoWCBrV8IAt5pOh4q9WRFNQy8Xj1TicyPRhx4nanrqFMwPZqJjdXJseCpzZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmFjdGlvbnMudjJkaGFzaFggB8VTvAwAD/ddMQXZYSRaq6SZIC1ht0Z6ZFz8EjZ2C4uiY3VybHgpc2VsZiNqdW1iZj1jMnBhLmFzc2VydGlvbnMvYzJwYS5oYXNoLmRhdGFkaGFzaFggW3k8MP+Lru9fMhn96/jjZqxlEkl9f9Jwd1ZbUuMgyDZ0Y2xhaW1fZ2VuZXJhdG9yX2luZm+jZG5hbWVvQW50aHJvcGljIEZpbGVzZ3ZlcnNpb25lMS4wLjBrc3BlY1ZlcnNpb25lMi40LjAAABA4anVtYgAAAChqdW1kYzJjcwARABCAAACqADibcQNjMnBhLnNpZ25hdHVyZQAAABAIY2JvctKEWQISogEmGCFZAgowggIGMIIBjaADAgECAhRA5aAK7sI50L64g/oGQgU9Z1UTADAKBggqhkjOPQQDAzBJMRcwFQYDVQQKEw5BbnRocm9waWMsIFBCQzEuMCwGA1UEAxMlQW50aHJvcGljIENvbnRlbnQgQ3JlZGVudGlhbHMgUm9vdCBDQTAeFw0yNjA4MDcxODQzNTZaFw0yODA4MDYxOTQzNTZaMEQxFzAVBgNVBAoTDkFudGhyb3BpYywgUEJDMSkwJwYDVQQDEyBBbnRocm9waWMgQ2xhdWRlIENvbnRlbnQgU2lnbmluZzBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABJh6CmvLUBgFFNU0vUKlOVtE6djd17L5SuwX0LemFisBM3dkd/3cyjxFA3Qo5S46fX0/ihY0VZ7mfb9KF703t5OjWDBWMA4GA1UdDwEB/wQEAwIHgDAVBgNVHSUEDjAMBgorBgEEAYPoXgIBMAwGA1UdEwEB/wQCMAAwHwYDVR0jBBgwFoAUzlHiBIFOZFsj+OPEz5o+nMHXXMIwCgYIKoZIzj0EAwMDZwAwZAIwMXMdFJ4BetLLVY7ORuE9noqbbAZOZn/aArXyTwFAZfKrPzxF2vPoJNf1+UCdg1XGAjBwX1zd9WGqYkqmL5SFqw1QySjr1zJfpJM9+1rdDwSPLMOPOjKuiXjoU/pUUeG9RwmhY3BhZFkNngAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPZYQCISpGvgqYgJIJrTs/lGf1+Zi/YUlbIQ1CM1JKl+NVYSktEvj8nfjJ+BKOnEoO26979lNpptMKIYpcdmWN7Q8yc=</c2pa:manifest></metadata></svg>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 28" width="900" height="28" shape-rendering="crispEdges" xmlns:c2pa="http://c2pa.org/manifest">
  <rect width="900" height="28" fill="#0b0f1a"/>
  <rect y="2" width="900" height="24" fill="#1d2140"/>
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0;-40,0" dur="1.6s" repeatCount="indefinite"/>
    <!-- top sprockets -->
    <g fill="#0b0f1a">
      <rect x="0" y="4" width="8" height="6"/><rect x="40" y="4" width="8" height="6"/><rect x="80" y="4" width="8" height="6"/><rect x="120" y="4" width="8" height="6"/><rect x="160" y="4" width="8" height="6"/><rect x="200" y="4" width="8" height="6"/><rect x="240" y="4" width="8" height="6"/><rect x="280" y="4" width="8" height="6"/><rect x="320" y="4" width="8" height="6"/><rect x="360" y="4" width="8" height="6"/><rect x="400" y="4" width="8" height="6"/><rect x="440" y="4" width="8" height="6"/><rect x="480" y="4" width="8" height="6"/><rect x="520" y="4" width="8" height="6"/><rect x="560" y="4" width="8" height="6"/><rect x="600" y="4" width="8" height="6"/><rect x="640" y="4" width="8" height="6"/><rect x="680" y="4" width="8" height="6"/><rect x="720" y="4" width="8" height="6"/><rect x="760" y="4" width="8" height="6"/><rect x="800" y="4" width="8" height="6"/><rect x="840" y="4" width="8" height="6"/><rect x="880" y="4" width="8" height="6"/><rect x="920" y="4" width="8" height="6"/>
    </g>
    <!-- bottom sprockets -->
    <g fill="#0b0f1a">
      <rect x="0" y="18" width="8" height="6"/><rect x="40" y="18" width="8" height="6"/><rect x="80" y="18" width="8" height="6"/><rect x="120" y="18" width="8" height="6"/><rect x="160" y="18" width="8" height="6"/><rect x="200" y="18" width="8" height="6"/><rect x="240" y="18" width="8" height="6"/><rect x="280" y="18" width="8" height="6"/><rect x="320" y="18" width="8" height="6"/><rect x="360" y="18" width="8" height="6"/><rect x="400" y="18" width="8" height="6"/><rect x="440" y="18" width="8" height="6"/><rect x="480" y="18" width="8" height="6"/><rect x="520" y="18" width="8" height="6"/><rect x="560" y="18" width="8" height="6"/><rect x="600" y="18" width="8" height="6"/><rect x="640" y="18" width="8" height="6"/><rect x="680" y="18" width="8" height="6"/><rect x="720" y="18" width="8" height="6"/><rect x="760" y="18" width="8" height="6"/><rect x="800" y="18" width="8" height="6"/><rect x="840" y="18" width="8" height="6"/><rect x="880" y="18" width="8" height="6"/><rect x="920" y="18" width="8" height="6"/>
    </g>
    <!-- frames -->
    <g>
      <rect x="14" y="11" width="20" height="6" fill="#4cc9f0"/>
      <rect x="94" y="11" width="20" height="6" fill="#f72585"/>
      <rect x="174" y="11" width="20" height="6" fill="#ffd166"/>
      <rect x="254" y="11" width="20" height="6" fill="#06d6a0"/>
      <rect x="334" y="11" width="20" height="6" fill="#4cc9f0"/>
      <rect x="414" y="11" width="20" height="6" fill="#f72585"/>
      <rect x="494" y="11" width="20" height="6" fill="#ffd166"/>
      <rect x="574" y="11" width="20" height="6" fill="#06d6a0"/>
      <rect x="654" y="11" width="20" height="6" fill="#4cc9f0"/>
      <rect x="734" y="11" width="20" height="6" fill="#f72585"/>
      <rect x="814" y="11" width="20" height="6" fill="#ffd166"/>
      <rect x="894" y="11" width="20" height="6" fill="#06d6a0"/>
    </g>
  </g>
<metadata><c2pa:manifest>AAAWgmp1bWIAAAAeanVtZGMycGEAEQAQgAAAqgA4m3EDYzJwYQAAABZcanVtYgAAAEdqdW1kYzJtYQARABCAAACqADibcQN1cm46YzJwYTpmYTFmMzVjNC1lMWUwLTQyMGItOGEzYS0yYjg2NDIzOGIxZTQAAAADl2p1bWIAAAApanVtZGMyYXMAEQAQgAAAqgA4m3EDYzJwYS5hc3NlcnRpb25zAAAAALxqdW1iAAAARGp1bWRjYm9yABEAEIAAAKoAOJtxE2MycGEuaW5ncmVkaWVudC52MwAAAAAYYzJzaIQj07PaTlkREzTUImPl9yoAAABwY2JvcqNpZGM6Zm9ybWF0bWltYWdlL3N2Zyt4bWxqaW5zdGFuY2VJRHgseG1wOmlpZDo2NTE3ZDcxMi1hZGYzLTQzN2EtOWVkZS0wOTVjODBiOTAyZTlscmVsYXRpb25zaGlwaHBhcmVudE9mAAAB4mp1bWIAAABBanVtZGNib3IAEQAQgAAAqgA4m3ETYzJwYS5hY3Rpb25zLnYyAAAAABhjMnNoNo29lp/LA3C41mACTRtNygAAAZljYm9yomdhY3Rpb25zgqJmYWN0aW9ua2MycGEub3BlbmVkanBhcmFtZXRlcnOha2luZ3JlZGllbnRzgaJjdXJseC1zZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmluZ3JlZGllbnQudjNkaGFzaFggWcAzENphSj420oM0o0rOvvzW+Esl4R23rvhyDus/5X2kZmFjdGlvbngdY29tLmFudGhyb3BpYy5jbGF1ZGUucHJvdmlkZWRqcGFyYW1ldGVyc6F4H2NvbS5hbnRocm9waWMub3JpZ2luLWNvbmZpZGVuY2VndW5rbm93bmtkZXNjcmlwdGlvbnhmQ2xhdWRlIHByb3ZpZGVkIHRoaXMgZmlsZSBhdCB0aGUgcmVxdWVzdCBvZiBhIHVzZXIgYW5kIG1heSBoYXZlIGNyZWF0ZWQgb3IgbW9kaWZpZWQgdGhlIGZpbGUgY29udGVudHMubXNvZnR3YXJlQWdlbnShZG5hbWVmQ2xhdWRlcmFsbEFjdGlvbnNJbmNsdWRlZPUAAADIanVtYgAAAEBqdW1kY2JvcgARABCAAACqADibcRNjMnBhLmhhc2guZGF0YQAAAAAYYzJzaD126jGR32URHlciTcrM1nsAAACAY2JvcqVjYWxnZnNoYTI1NmNwYWRMAAAAAAAAAAAAAAAAZGhhc2hYIHrMkh9kpS4evvwI60ZRz19Yhy8hvt87prrfCmjD4d/hZG5hbWVuanVtYmYgbWFuaWZlc3RqZXhjbHVzaW9uc4GiZXN0YXJ0GQ1TZmxlbmd0aBkeBAAAAj5qdW1iAAAAJ2p1bWRjMmNsABEAEIAAAKoAOJtxA2MycGEuY2xhaW0udjIAAAACD2Nib3KlY2FsZ2ZzaGEyNTZpc2lnbmF0dXJleE1zZWxmI2p1bWJmPS9jMnBhL3VybjpjMnBhOmZhMWYzNWM0LWUxZTAtNDIwYi04YTNhLTJiODY0MjM4YjFlNC9jMnBhLnNpZ25hdHVyZWppbnN0YW5jZUlEeCx4bXA6aWlkOjk1YTUxNDIzLWZlMjAtNDhmYS05YzYxLTI2ZTcyYzg1NWY5NXJjcmVhdGVkX2Fzc2VydGlvbnODomN1cmx4LXNlbGYjanVtYmY9YzJwYS5hc3NlcnRpb25zL2MycGEuaW5ncmVkaWVudC52M2RoYXNoWCBZwDMQ2mFKPjbSgzSjSs6+/Nb4SyXhHbeu+HIO6z/lfaJjdXJseCpzZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmFjdGlvbnMudjJkaGFzaFggMl1irDCuPGLx/+4Wwe0uo8YsiVhgfDuOoRpyWwVqwWiiY3VybHgpc2VsZiNqdW1iZj1jMnBhLmFzc2VydGlvbnMvYzJwYS5oYXNoLmRhdGFkaGFzaFgg4h1AeQg5IFrQwaCyUFr+JFl/7enjr44z0rIK2r16yZd0Y2xhaW1fZ2VuZXJhdG9yX2luZm+jZG5hbWVvQW50aHJvcGljIEZpbGVzZ3ZlcnNpb25lMS4wLjBrc3BlY1ZlcnNpb25lMi40LjAAABA4anVtYgAAAChqdW1kYzJjcwARABCAAACqADibcQNjMnBhLnNpZ25hdHVyZQAAABAIY2JvctKEWQISogEmGCFZAgowggIGMIIBjaADAgECAhRA5aAK7sI50L64g/oGQgU9Z1UTADAKBggqhkjOPQQDAzBJMRcwFQYDVQQKEw5BbnRocm9waWMsIFBCQzEuMCwGA1UEAxMlQW50aHJvcGljIENvbnRlbnQgQ3JlZGVudGlhbHMgUm9vdCBDQTAeFw0yNjA4MDcxODQzNTZaFw0yODA4MDYxOTQzNTZaMEQxFzAVBgNVBAoTDkFudGhyb3BpYywgUEJDMSkwJwYDVQQDEyBBbnRocm9waWMgQ2xhdWRlIENvbnRlbnQgU2lnbmluZzBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABJh6CmvLUBgFFNU0vUKlOVtE6djd17L5SuwX0LemFisBM3dkd/3cyjxFA3Qo5S46fX0/ihY0VZ7mfb9KF703t5OjWDBWMA4GA1UdDwEB/wQEAwIHgDAVBgNVHSUEDjAMBgorBgEEAYPoXgIBMAwGA1UdEwEB/wQCMAAwHwYDVR0jBBgwFoAUzlHiBIFOZFsj+OPEz5o+nMHXXMIwCgYIKoZIzj0EAwMDZwAwZAIwMXMdFJ4BetLLVY7ORuE9noqbbAZOZn/aArXyTwFAZfKrPzxF2vPoJNf1+UCdg1XGAjBwX1zd9WGqYkqmL5SFqw1QySjr1zJfpJM9+1rdDwSPLMOPOjKuiXjoU/pUUeG9RwmhY3BhZFkNngAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPZYQPQrtP1Foki2UU0IKObxoH5SdvcMSsmRud+y/4Wx65RV44pGnikAlkfqVXe30banTDENz+9+cYBRMMHrOVqhC3Q=</c2pa:manifest></metadata></svg>

<!-- ============ HEADER ============ -->
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=120&section=header" width="100%" />

<img src="./assets/banner.svg" alt="Miguel Terence Jarin - pixel laptop and camera banner" width="100%" />

<a href="https://github.com/yeyensmoves">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=800&color=4CC9F0&center=true&vCenter=true&width=640&lines=Frontend+Developer+%F0%9F%92%BB;Video+Editor+%F0%9F%8E%AC;Photographer+%F0%9F%93%B8;Creative+Technologist+%E2%9C%A8;Building+digital+experiences+%26+visual+stories" alt="Typing animation" />
</a>

<br/>

📍 Philippines 🇵🇭

<img src="https://komarev.com/ghpvc/?username=yeyensmoves&label=Profile%20Views&color=203A43&style=for-the-badge" alt="Profile views" />

[![GitHub](https://img.shields.io/badge/GitHub-yeyensmoves-181717?style=for-the-badge&logo=github)](https://github.com/yeyensmoves)
[![Facebook](https://img.shields.io/badge/Facebook-Connect-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/miguelterence.jarin)
[![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/yeeyeeenz_/)

</div>

<img src="./assets/divider.svg" width="100%" alt="film strip divider" />

<!-- ============ ABOUT ============ -->
## 💫 About Me

```js
const miguel = {
  name: "Miguel Terence Jarin",
  handle: "yeyensmoves",
  location: "Philippines 🇵🇭",
  roles: ["Frontend Developer", "Video Editor", "Creative Technologist"],
  currentlyLearning: ["Full-stack development", "UI/UX design", "Better storytelling"],
  hobbies: ["Photography 📸", "Videography 🎥", "Video editing 🎬", "Building websites 💻"],
  funFact: "I like turning code and camera footage into experiences people remember."
};
```

- 💻 Interested in **frontend & full-stack** web development
- 🎨 Passionate about **UI/UX design** and creative visuals
- 🎬 Experienced in **photography, videography & video editing**
- 🌱 Constantly learning and levelling up my dev skills
- 🚀 Building **meaningful and practical** digital projects

<img src="./assets/divider.svg" width="100%" alt="film strip divider" />

<!-- ============ HOBBIES ============ -->
## 🎮 What I Love Doing

<div align="center">
  <img src="./assets/hobbies.svg" alt="Pixel art: camera for photography, clapperboard for video editing, laptop for coding" width="100%" />
</div>

<img src="./assets/divider.svg" width="100%" alt="film strip divider" />

<!-- ============ TECH STACK ============ -->
## 🛠️ Tech Stack

**Languages**

<p align="left">
  <img src="https://skillicons.dev/icons?i=html,css,js,php,python" />
</p>

**Frameworks & Technologies**

<p align="left">
  <img src="https://skillicons.dev/icons?i=nodejs,express,android,opencv,tensorflow" />
</p>

**Databases & Cloud**

<p align="left">
  <img src="https://skillicons.dev/icons?i=mysql,postgres,sqlite,gcp" />
</p>

**Design & Creative Tools**

<p align="left">
  <img src="https://skillicons.dev/icons?i=figma,ps,pr,ae" />
</p>

**Development Environment**

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,linux" />
</p>

<img src="./assets/divider.svg" width="100%" alt="film strip divider" />

<!-- ============ ANALYTICS ============ -->
## 📊 GitHub Analytics

<div align="center">

<img width="49%" src="https://github-stats-extended.vercel.app/api?username=yeyensmoves&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github" alt="GitHub Stats" />
<img width="49%" src="https://github-stats-extended.vercel.app/api/top-langs/?username=yeyensmoves&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Top Languages" />

<br/>

<img width="70%" src="https://streak-stats.demolab.com?user=yeyensmoves&theme=tokyonight&hide_border=true&border_radius=10" alt="GitHub Contribution Streak" />

</div>

<img src="./assets/divider.svg" width="100%" alt="film strip divider" />

<!-- ============ CONNECT ============ -->
## 🤝 Let's Connect!

<div align="center">

I'm always open to learning, collaborating, and building creative projects. 📸💻🎬

<a href="https://github.com/yeyensmoves">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>
<a href="https://www.facebook.com/miguelterence.jarin">
  <img src="https://img.shields.io/badge/Facebook-1877F2?style=for-the-badge&logo=facebook&logoColor=white" />
</a>
<a href="https://www.instagram.com/yeeyeeenz_/">
  <img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" />
</a>

<br/><br/>

**Thanks for visiting my profile!** ⭐

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=100&section=footer" width="100%" />

</div>

<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 900 240" width="900" height="240" shape-rendering="crispEdges" xmlns:c2pa="http://c2pa.org/manifest">
  <rect width="900" height="240" fill="#0b0f1a"/>

  <!-- tiles -->
  <g fill="#1d2140">
    <rect x="30" y="20" width="250" height="200"/>
    <rect x="325" y="20" width="250" height="200"/>
    <rect x="620" y="20" width="250" height="200"/>
  </g>
  <g fill="none" stroke="#4cc9f0" stroke-width="4">
    <rect x="32" y="22" width="246" height="196"/>
  </g>
  <g fill="none" stroke="#f72585" stroke-width="4">
    <rect x="327" y="22" width="246" height="196"/>
  </g>
  <g fill="none" stroke="#06d6a0" stroke-width="4">
    <rect x="622" y="22" width="246" height="196"/>
  </g>

  <!-- ===== CAMERA (photography) ===== -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-8;0,0" dur="2.4s" repeatCount="indefinite"/>
    <rect x="100" y="64" width="40" height="12" fill="#3a4170"/>
    <rect x="76" y="76" width="108" height="64" fill="#2d3250"/>
    <rect x="76" y="76" width="108" height="6" fill="#3a4170"/>
    <rect x="160" y="68" width="14" height="8" fill="#f72585"/>
    <rect x="106" y="86" width="48" height="48" fill="#0b0f1a"/>
    <rect x="112" y="92" width="36" height="36" fill="#3a86ff"/>
    <rect x="120" y="100" width="20" height="20" fill="#0b0f1a"/>
    <rect x="124" y="104" width="6" height="6" fill="#fff"><animate attributeName="opacity" values="1;0.2;1" dur="1.6s" repeatCount="indefinite"/></rect>
    <rect x="84" y="84" width="8" height="8" fill="#ffd166"><animate attributeName="opacity" values="1;0;1" dur="1.8s" repeatCount="indefinite"/></rect>
  </g>
  <text x="155" y="196" text-anchor="middle" font-family="'Courier New', monospace" font-size="16" font-weight="bold" fill="#4cc9f0">PHOTOGRAPHY</text>

  <!-- ===== CLAPPERBOARD (video editing) ===== -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-8;0,0" dur="2.4s" begin="0.8s" repeatCount="indefinite"/>
    <!-- board -->
    <rect x="390" y="92" width="120" height="56" fill="#2d3250"/>
    <rect x="398" y="104" width="104" height="4" fill="#5c6784"/>
    <rect x="398" y="116" width="72" height="4" fill="#5c6784"/>
    <rect x="398" y="128" width="88" height="4" fill="#5c6784"/>
    <!-- clapper top (opens/closes) -->
    <g>
      <animateTransform attributeName="transform" type="rotate" values="0 390 88;-14 390 88;0 390 88;0 390 88" keyTimes="0;0.15;0.3;1" dur="2.4s" begin="0.8s" repeatCount="indefinite"/>
      <rect x="390" y="72" width="120" height="16" fill="#111"/>
      <rect x="398" y="72" width="16" height="16" fill="#fff"/>
      <rect x="430" y="72" width="16" height="16" fill="#fff"/>
      <rect x="462" y="72" width="16" height="16" fill="#fff"/>
      <rect x="494" y="72" width="16" height="16" fill="#fff"/>
    </g>
    <!-- play triangle pixels -->
    <rect x="474" y="112" width="6" height="18" fill="#f72585"/>
    <rect x="480" y="116" width="6" height="10" fill="#f72585"/>
  </g>
  <text x="450" y="196" text-anchor="middle" font-family="'Courier New', monospace" font-size="16" font-weight="bold" fill="#f72585">VIDEO EDITING</text>

  <!-- ===== LAPTOP (coding) ===== -->
  <g>
    <animateTransform attributeName="transform" type="translate" values="0,0;0,-8;0,0" dur="2.4s" begin="1.6s" repeatCount="indefinite"/>
    <rect x="690" y="72" width="110" height="72" fill="#8892b0"/>
    <rect x="694" y="76" width="102" height="64" fill="#0b0f1a"/>
    <!-- </> symbol -->
    <g fill="#06d6a0">
      <rect x="708" y="102" width="6" height="6"/><rect x="702" y="108" width="6" height="6"/><rect x="708" y="114" width="6" height="6"/>
      <rect x="776" y="102" width="6" height="6"/><rect x="782" y="108" width="6" height="6"/><rect x="776" y="114" width="6" height="6"/>
    </g>
    <g fill="#ffd166">
      <rect x="748" y="94" width="6" height="8"/><rect x="744" y="102" width="6" height="8"/><rect x="740" y="110" width="6" height="8"/><rect x="736" y="118" width="6" height="8"/>
    </g>
    <rect x="720" y="130" width="6" height="6" fill="#fff"><animate attributeName="opacity" values="1;0;1" dur="0.9s" repeatCount="indefinite"/></rect>
    <rect x="678" y="144" width="134" height="8" fill="#8892b0"/>
    <rect x="726" y="144" width="38" height="3" fill="#5c6784"/>
  </g>
  <text x="745" y="196" text-anchor="middle" font-family="'Courier New', monospace" font-size="16" font-weight="bold" fill="#06d6a0">CODING</text>

  <!-- sparkles -->
  <g fill="#ffd166">
    <rect x="50" y="40" width="4" height="4"><animate attributeName="opacity" values="1;0;1" dur="1.4s" repeatCount="indefinite"/></rect>
    <rect x="540" y="44" width="4" height="4"><animate attributeName="opacity" values="0;1;0" dur="1.7s" repeatCount="indefinite"/></rect>
    <rect x="840" y="40" width="4" height="4"><animate attributeName="opacity" values="1;0;1" dur="2s" repeatCount="indefinite"/></rect>
  </g>
<metadata><c2pa:manifest>AAAWgmp1bWIAAAAeanVtZGMycGEAEQAQgAAAqgA4m3EDYzJwYQAAABZcanVtYgAAAEdqdW1kYzJtYQARABCAAACqADibcQN1cm46YzJwYTo3MjU1ZTZlOS05NDQyLTQwYTYtYWMyNC0zMTU0NTE4ZjE2ZmEAAAADl2p1bWIAAAApanVtZGMyYXMAEQAQgAAAqgA4m3EDYzJwYS5hc3NlcnRpb25zAAAAALxqdW1iAAAARGp1bWRjYm9yABEAEIAAAKoAOJtxE2MycGEuaW5ncmVkaWVudC52MwAAAAAYYzJzaL8h5vey1xA5mrVhaU0sanEAAABwY2JvcqNpZGM6Zm9ybWF0bWltYWdlL3N2Zyt4bWxqaW5zdGFuY2VJRHgseG1wOmlpZDo3ODA4NzE1ZC1lN2FiLTQ0ZDEtYmE3OC04YzM4NDRjMzQ3MGZscmVsYXRpb25zaGlwaHBhcmVudE9mAAAB4mp1bWIAAABBanVtZGNib3IAEQAQgAAAqgA4m3ETYzJwYS5hY3Rpb25zLnYyAAAAABhjMnNo/g5ycOoPqdq6fVL/dEKq3AAAAZljYm9yomdhY3Rpb25zgqJmYWN0aW9ua2MycGEub3BlbmVkanBhcmFtZXRlcnOha2luZ3JlZGllbnRzgaJjdXJseC1zZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmluZ3JlZGllbnQudjNkaGFzaFggFVVbdxqz7Ssn6pEWIfOmmPORdjccZ7+jyGv/veOjobKkZmFjdGlvbngdY29tLmFudGhyb3BpYy5jbGF1ZGUucHJvdmlkZWRqcGFyYW1ldGVyc6F4H2NvbS5hbnRocm9waWMub3JpZ2luLWNvbmZpZGVuY2VndW5rbm93bmtkZXNjcmlwdGlvbnhmQ2xhdWRlIHByb3ZpZGVkIHRoaXMgZmlsZSBhdCB0aGUgcmVxdWVzdCBvZiBhIHVzZXIgYW5kIG1heSBoYXZlIGNyZWF0ZWQgb3IgbW9kaWZpZWQgdGhlIGZpbGUgY29udGVudHMubXNvZnR3YXJlQWdlbnShZG5hbWVmQ2xhdWRlcmFsbEFjdGlvbnNJbmNsdWRlZPUAAADIanVtYgAAAEBqdW1kY2JvcgARABCAAACqADibcRNjMnBhLmhhc2guZGF0YQAAAAAYYzJzaE0NAt275S7bd4Joxfgd4wgAAACAY2JvcqVjYWxnZnNoYTI1NmNwYWRMAAAAAAAAAAAAAAAAZGhhc2hYIMmt/lBiUjie6yc5hacww0aidLl8U81ertcWjT4i8LxlZG5hbWVuanVtYmYgbWFuaWZlc3RqZXhjbHVzaW9uc4GiZXN0YXJ0GRN+Zmxlbmd0aBkeBAAAAj5qdW1iAAAAJ2p1bWRjMmNsABEAEIAAAKoAOJtxA2MycGEuY2xhaW0udjIAAAACD2Nib3KlY2FsZ2ZzaGEyNTZpc2lnbmF0dXJleE1zZWxmI2p1bWJmPS9jMnBhL3VybjpjMnBhOjcyNTVlNmU5LTk0NDItNDBhNi1hYzI0LTMxNTQ1MThmMTZmYS9jMnBhLnNpZ25hdHVyZWppbnN0YW5jZUlEeCx4bXA6aWlkOmQ4OTE1MGQyLWU5YjQtNGJmMC1iYzhmLTVlNjIwMjYzZGM2YXJjcmVhdGVkX2Fzc2VydGlvbnODomN1cmx4LXNlbGYjanVtYmY9YzJwYS5hc3NlcnRpb25zL2MycGEuaW5ncmVkaWVudC52M2RoYXNoWCAVVVt3GrPtKyfqkRYh86aY85F2Nxxnv6PIa/+946OhsqJjdXJseCpzZWxmI2p1bWJmPWMycGEuYXNzZXJ0aW9ucy9jMnBhLmFjdGlvbnMudjJkaGFzaFgg3bAxY6hvVe9TcajpvbeYAon0n0d0UKpchTm75+YEfQeiY3VybHgpc2VsZiNqdW1iZj1jMnBhLmFzc2VydGlvbnMvYzJwYS5oYXNoLmRhdGFkaGFzaFgg0BcpYnFKYuID8EQSaD3XDAs08HOiwwUrBEdZR1sg/fJ0Y2xhaW1fZ2VuZXJhdG9yX2luZm+jZG5hbWVvQW50aHJvcGljIEZpbGVzZ3ZlcnNpb25lMS4wLjBrc3BlY1ZlcnNpb25lMi40LjAAABA4anVtYgAAAChqdW1kYzJjcwARABCAAACqADibcQNjMnBhLnNpZ25hdHVyZQAAABAIY2JvctKEWQISogEmGCFZAgowggIGMIIBjaADAgECAhRA5aAK7sI50L64g/oGQgU9Z1UTADAKBggqhkjOPQQDAzBJMRcwFQYDVQQKEw5BbnRocm9waWMsIFBCQzEuMCwGA1UEAxMlQW50aHJvcGljIENvbnRlbnQgQ3JlZGVudGlhbHMgUm9vdCBDQTAeFw0yNjA4MDcxODQzNTZaFw0yODA4MDYxOTQzNTZaMEQxFzAVBgNVBAoTDkFudGhyb3BpYywgUEJDMSkwJwYDVQQDEyBBbnRocm9waWMgQ2xhdWRlIENvbnRlbnQgU2lnbmluZzBZMBMGByqGSM49AgEGCCqGSM49AwEHA0IABJh6CmvLUBgFFNU0vUKlOVtE6djd17L5SuwX0LemFisBM3dkd/3cyjxFA3Qo5S46fX0/ihY0VZ7mfb9KF703t5OjWDBWMA4GA1UdDwEB/wQEAwIHgDAVBgNVHSUEDjAMBgorBgEEAYPoXgIBMAwGA1UdEwEB/wQCMAAwHwYDVR0jBBgwFoAUzlHiBIFOZFsj+OPEz5o+nMHXXMIwCgYIKoZIzj0EAwMDZwAwZAIwMXMdFJ4BetLLVY7ORuE9noqbbAZOZn/aArXyTwFAZfKrPzxF2vPoJNf1+UCdg1XGAjBwX1zd9WGqYkqmL5SFqw1QySjr1zJfpJM9+1rdDwSPLMOPOjKuiXjoU/pUUeG9RwmhY3BhZFkNngAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAPZYQHLvSth2TleYkorfE0cK3ApYmvi+z1VAnqu8Wfe1Lh9ClF2pzPT9uozeD/eRgOj3oDjXQxhEA2D1jNrCB1C3Q8s=</c2pa:manifest></metadata></svg>




