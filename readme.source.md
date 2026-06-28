
```aura width=860 height=240 link="https://github.com/GreyNova"
<div style={{
  width: '100%', height: '100%', background: '#08080c',
  display: 'flex', alignItems: 'center', fontFamily: 'Inter, sans-serif',
  position: 'relative', overflow: 'hidden', borderRadius: 16,
  border: '1px solid rgba(0, 255, 136, 0.2)'
}}>

  <style>{`
      @keyframes float-slow {
        0%, 100% { transform: translateX(0px); opacity: 0.8; }
        50% { transform: translateX(350px); opacity: 1.2; }
      }
      @keyframes float-medium {
        0%, 100% { transform: translateX(0px); opacity: 0.7; }
        50% { transform: translateX(-250px); opacity: 1.1; }
      }
      @keyframes float-pulse {
        0%, 100% { transform: scale(1); opacity: 0.8; }
        50% { transform: scale(1.3); opacity: 0.4; }
      }
      #glow-1 { animation: float-slow 8s ease-in-out infinite; }
      #glow-2 { animation: float-medium 12s ease-in-out infinite; }
      #glow-3 { animation: float-pulse 7s ease-in-out infinite; }
    `}</style>

  <svg width="860" height="240" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="g1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0, 255, 136, 0.4)" />
        <stop offset="40%" stopColor="rgba(0, 255, 136, 0.15)" />
        <stop offset="70%" stopColor="rgba(0, 255, 136, 0)" />
      </radialGradient>
      <radialGradient id="g2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(0, 195, 255, 0.4)" />
        <stop offset="45%" stopColor="rgba(0, 195, 255, 0.15)" />
        <stop offset="70%" stopColor="rgba(0, 195, 255, 0)" />
      </radialGradient>
      <radialGradient id="g3" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(110, 20, 210, 0.3)" />
        <stop offset="50%" stopColor="rgba(110, 20, 210, 0.1)" />
        <stop offset="70%" stopColor="rgba(110, 20, 210, 0)" />
      </radialGradient>
    </defs>

    <ellipse id="glow-1" cx="200" cy="230" rx="300" ry="200" fill="url(#g1)" />
    <ellipse id="glow-2" cx="600" cy="240" rx="250" ry="180" fill="url(#g2)" />
    <ellipse id="glow-3" cx="420" cy="240" rx="200" ry="150" fill="url(#g3)" />
  </svg>

  <div style={{
    position: 'absolute', left: 48, top: 72, width: 96, height: 96,
    borderRadius: 48, background: 'linear-gradient(135deg, #00ff88, #00c3ff)',
    display: 'flex', alignItems: 'center', justifyContent: 'center',
    boxShadow: '0 0 20px rgba(0, 255, 136, 0.4)'
  }}>
    <img src="https://github.com/GreyNova.png" width={88} height={88} style={{ borderRadius: 44 }} />
  </div>

  <div style={{ display:'flex', flexDirection:'column', marginLeft:168, gap:8, zIndex: 10 }}>
    <div style={{ display:'flex', fontSize:38, fontWeight:800, color:'#ffffff', letterSpacing:'-1px', lineHeight:1 }}>
      Anash (GreyNova)
    </div>
    <div style={{ display:'flex', fontSize:16, color:'rgba(255,255,255,0.7)', fontWeight:400, letterSpacing:'0.3px', marginTop: 4 }}>
      Full Stack Developer • AI/ML Enthusiast • Open Source Contributor
    </div>
    <div style={{ display:'flex', gap:8, marginTop:12, flexWrap: 'wrap' }}>
      {['JavaScript', 'TypeScript', 'Python', 'React', 'Jupyter', 'CSS'].map(function(tag, i) {
        return (
          <div key={tag} style={{
            display:'flex', padding:'6px 14px', borderRadius:20,
            background:'rgba(0, 255, 136, 0.1)', border:'1px solid rgba(0, 255, 136, 0.3)',
            color:'#00ff88', fontSize:12, fontWeight:600,
          }}>{tag}</div>
        );
      })}
    </div>
  </div>
</div>
```

```aura width=150 height=44 link="mailto:anashg85@gmail.com" inline align=center
<SocialMediaButton
  text="Email Me"
  backgroundColor="#0f0f13"
  width={150}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#00ff88' },
    { offset: '50%', color: '#00c3ff' },
    { offset: '100%', color: '#00ff88' },
  ]}
/>
```
```aura width=150 height=44 link="https://github.com/GreyNova" inline align=center
<SocialMediaButton
  text="GitHub"
  backgroundColor="#0f0f13"
  width={150}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffffff' },
    { offset: '50%', color: '#888888' },
    { offset: '100%', color: '#ffffff' },
  ]}
/>
```

```aura width=860 height=22 link="https://github.com/GreyNova"
  <div style={{ display: 'flex', justifyContent: 'center', alignItems: 'center', width: '100%', height: '100%', padding: 0, margin: 0 }}>
    <span style={{ fontSize: 12, lineHeight: 1, color: 'rgba(150,140,200,0.55)', fontWeight: 500, letterSpacing: '0.4px' }}>powered by readme-aura</span>
  </div>
```
