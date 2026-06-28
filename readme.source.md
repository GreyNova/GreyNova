
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
  </div>
</div>
```

```aura width=150 height=44 link="https://mail.google.com/mail/?view=cm&fs=1&to=anashg85@gmail.com&su=Hello%20Anash" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/gmail/ffffff"
  text="Email"
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
```aura width=150 height=44 link="https://leetcode.com/u/anashg85/" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/leetcode/ffffff"
  text="LeetCode"
  backgroundColor="#0f0f13"
  width={150}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#ffa116' },
    { offset: '50%', color: '#ffb94f' },
    { offset: '100%', color: '#ffa116' },
  ]}
/>
```
```aura width=150 height=44 link="https://portfolio-t8rl.vercel.app/" inline align=center
<SocialMediaButton
  icon="https://cdn.simpleicons.org/vercel/ffffff"
  text="Portfolio"
  backgroundColor="#0f0f13"
  width={150}
  height={44}
  gradientStops={[
    { offset: '0%', color: '#aa00ff' },
    { offset: '50%', color: '#e040fb' },
    { offset: '100%', color: '#aa00ff' },
  ]}
/>
```
```aura width=860 height=240
<div style={{
  width: '100%', height: '100%', background: '#0a0a0f',
  display: 'flex', flexDirection: 'column', alignItems: 'center', justifyContent: 'center',
  fontFamily: 'Inter, sans-serif', position: 'relative', overflow: 'hidden',
  borderRadius: 16, border: '1px solid rgba(255,255,255,0.05)'
}}>
  <style>{`
      @keyframes soft-pulse1 { 0%, 100% { opacity: 0.3; } 50% { opacity: 0.6; } }
      @keyframes soft-pulse2 { 0%, 100% { opacity: 0.2; } 50% { opacity: 0.5; } }
      #bg-glow-1 { animation: soft-pulse1 6s ease-in-out infinite; }
      #bg-glow-2 { animation: soft-pulse2 8s ease-in-out infinite 2s; }
  `}</style>
  <svg width="860" height="240" style={{ position: 'absolute', top: 0, left: 0 }}>
    <defs>
      <radialGradient id="stack-g1" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(80, 200, 120, 0.25)" />
        <stop offset="100%" stopColor="rgba(80, 200, 120, 0)" />
      </radialGradient>
      <radialGradient id="stack-g2" cx="50%" cy="50%" r="50%">
        <stop offset="0%" stopColor="rgba(60, 130, 255, 0.2)" />
        <stop offset="100%" stopColor="rgba(60, 130, 255, 0)" />
      </radialGradient>
    </defs>
    <ellipse id="bg-glow-1" cx="150" cy="240" rx="300" ry="150" fill="url(#stack-g1)" />
    <ellipse id="bg-glow-2" cx="700" cy="240" rx="300" ry="150" fill="url(#stack-g2)" />
  </svg>

  <span style={{ fontSize: 11, fontWeight: 700, color: 'rgba(255,255,255,0.4)', letterSpacing: '4px', marginBottom: 18, zIndex: 10 }}>STACK</span>

  <div style={{ display: 'flex', flexDirection: 'column', alignItems: 'center', gap: 8, zIndex: 10 }}>
    <span style={{ fontSize: 10, fontWeight: 600, color: 'rgba(120,200,150,0.55)', letterSpacing: '2px', marginBottom: 4 }}>LANGUAGES</span>
    <div style={{ display: 'flex', gap: 10 }}>
      {['Python', 'TypeScript', 'JavaScript', 'PHP', 'SQL'].map((tech) => (
        <span key={tech} style={{ padding: '6px 16px', background: 'rgba(255,255,255,0.04)', border: '1px solid rgba(255,255,255,0.06)', borderRadius: 20, color: 'rgba(255,255,255,0.78)', fontSize: 13, fontWeight: 500 }}>{tech}</span>
      ))}
    </div>
    <span style={{ fontSize: 10, fontWeight: 600, color: 'rgba(120,150,255,0.55)', letterSpacing: '2px', marginTop: 6, marginBottom: 4 }}>AI / MACHINE LEARNING</span>
    <div style={{ display: 'flex', gap: 10 }}>
      {['Hugging Face', 'OpenCV', 'TensorFlow', 'Pandas', 'NumPy'].map((tech) => (
        <span key={tech} style={{ padding: '6px 16px', background: 'rgba(255,255,255,0.04)', border: '1px solid rgba(255,255,255,0.06)', borderRadius: 20, color: 'rgba(255,255,255,0.78)', fontSize: 13, fontWeight: 500 }}>{tech}</span>
      ))}
    </div>
    <span style={{ fontSize: 10, fontWeight: 600, color: 'rgba(180,120,255,0.55)', letterSpacing: '2px', marginTop: 6, marginBottom: 4 }}>WEB & TOOLS</span>
    <div style={{ display: 'flex', gap: 10 }}>
      {['React', 'Node.js', 'FastAPI', 'Solidity', 'Git', 'Docker'].map((tech) => (
        <span key={tech} style={{ padding: '6px 16px', background: 'rgba(255,255,255,0.04)', border: '1px solid rgba(255,255,255,0.06)', borderRadius: 20, color: 'rgba(255,255,255,0.78)', fontSize: 13, fontWeight: 500 }}>{tech}</span>
      ))}
    </div>
  </div>
</div>
```

```aura width=860 height=22 link="https://github.com/GreyNova"
  <div style={{ display: 'flex', justifyContent: 'center', alignItems: 'center', width: '100%', height: '100%', padding: 0, margin: 0 }}>
    <span style={{ fontSize: 12, lineHeight: 1, color: 'rgba(150,140,200,0.55)', fontWeight: 500, letterSpacing: '0.4px' }}>powered by readme-aura</span>
  </div>
```
