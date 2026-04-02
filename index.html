<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=0"/>
<title>For Junaid Khan</title>
<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:ital,wght@0,300;0,400;0,500;1,300;1,400&family=Syne:wght@400;500;600;700&family=DM+Mono:wght@300;400&display=swap" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>
<style>
:root{
  --bg:#040404;--surface:#0d0d0d;--surface2:#111;--surface3:#171717;
  --border:rgba(255,255,255,0.05);--border-hi:rgba(255,255,255,0.12);
  --gold:#c9a96e;--gold-dim:#a07e4a;--gold-glow:rgba(201,169,110,0.22);
  --gold-faint:rgba(201,169,110,0.07);--gold-bright:#e8c97a;
  --text:#e8e0d4;--text-muted:#6e6560;--text-dim:#2e2a25;--white:#f5f0e8;
  --cursor-size:18px;
}
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent;}
html,body{overflow:hidden!important;width:100%;height:100%;position:fixed;}
body{
  font-family:'Syne',sans-serif;background:var(--bg);
  height:100vh;display:flex;align-items:center;justify-content:center;
  color:var(--text);cursor:none;touch-action:manipulation;
}

/* ── CUSTOM CURSOR ── */
#cursor{
  position:fixed;width:var(--cursor-size);height:var(--cursor-size);
  border-radius:50%;pointer-events:none;z-index:99999;
  mix-blend-mode:screen;transition:transform 0.15s ease,opacity 0.3s;
  background:radial-gradient(circle,rgba(201,169,110,0.9),rgba(201,169,110,0));
  transform:translate(-50%,-50%);will-change:left,top;
}
#cursor-trail{position:fixed;pointer-events:none;z-index:99998;inset:0;}
#cursor-trail canvas{position:absolute;inset:0;width:100%;height:100%;}

/* ── WEBGL / STAR CANVAS ── */
#starCanvas{
  position:fixed;inset:0;width:100%;height:100%;z-index:0;
  pointer-events:none;opacity:0.85;
}

/* ── GRAIN ── */
body::before{
  content:'';position:fixed;inset:0;
  background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 512 512' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.75' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
  pointer-events:none;z-index:9998;opacity:0.6;mix-blend-mode:overlay;
}

/* ── PROGRESS ── */
.progress-container{position:fixed;top:0;left:0;right:0;height:1px;background:rgba(255,255,255,0.03);z-index:1000;}
.progress-bar{
  height:100%;width:0%;
  background:linear-gradient(90deg,transparent,var(--gold-dim),var(--gold),var(--gold-dim));
  background-size:200% 100%;
  transition:width 1.2s cubic-bezier(0.65,0,0.35,1);
  animation:progressShimmer 3s linear infinite;
  box-shadow:0 0 10px var(--gold-glow),0 0 20px var(--gold-faint);
}
@keyframes progressShimmer{0%{background-position:100% 0}100%{background-position:-100% 0}}

/* ── MUSIC ── */
.music-control{
  position:fixed;top:20px;right:20px;width:40px;height:40px;
  border-radius:50%;background:rgba(13,13,13,0.85);
  backdrop-filter:blur(16px);-webkit-backdrop-filter:blur(16px);
  border:1px solid var(--border);cursor:none;
  display:flex;align-items:center;justify-content:center;
  font-size:0.95rem;transition:all 0.4s cubic-bezier(0.34,1.56,0.64,1);
  z-index:1000;color:var(--text-muted);
}
.music-control:hover{border-color:var(--gold-dim);color:var(--gold);box-shadow:0 0 24px var(--gold-faint);}
.music-control.playing{border-color:rgba(201,169,110,0.35);color:var(--gold);animation:musicPulse 2s ease-in-out infinite;}
@keyframes musicPulse{0%,100%{box-shadow:0 0 12px var(--gold-faint)}50%{box-shadow:0 0 28px var(--gold-glow)}}

/* ── PAGES ── */
.page{
  display:none;
  background:linear-gradient(160deg,#0f0f0f 0%,#0a0a0a 100%);
  width:92%;max-width:460px;border-radius:6px;padding:52px 36px;
  text-align:center;border:1px solid var(--border);
  box-shadow:0 0 0 1px rgba(255,255,255,0.015),0 2px 0 rgba(255,255,255,0.025),0 48px 100px rgba(0,0,0,0.75),0 0 80px rgba(201,169,110,0.04);
  position:relative;z-index:10;max-height:88vh;overflow-y:auto;
  -webkit-overflow-scrolling:touch;will-change:transform,opacity;
}
.page::before{
  content:'';position:absolute;top:0;left:10%;right:10%;height:1px;
  background:linear-gradient(90deg,transparent,rgba(255,255,255,0.08),transparent);
  border-radius:100%;pointer-events:none;
}
.page::-webkit-scrollbar{width:2px;}
.page::-webkit-scrollbar-track{background:transparent;}
.page::-webkit-scrollbar-thumb{background:var(--gold-dim);border-radius:4px;}
.page.active{display:block;animation:pageEnter 1s cubic-bezier(0.16,1,0.3,1) both;}
@keyframes pageEnter{
  from{opacity:0;transform:translateY(36px) scale(0.96);filter:blur(6px);}
  to{opacity:1;transform:translateY(0) scale(1);filter:blur(0);}
}
.page.exit-stage-1{animation:exitPage 0.6s cubic-bezier(0.55,0,1,0.45) forwards;pointer-events:none;}
@keyframes exitPage{to{opacity:0;transform:translateY(-30px) scale(0.95);filter:blur(10px);}}

/* ── RULE ── */
.rule{width:40px;height:1px;background:linear-gradient(90deg,transparent,var(--gold-dim),transparent);margin:0 auto 38px;position:relative;}
.rule::before{content:'✦';position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);font-size:0.45rem;color:var(--gold-dim);background:#0d0d0d;padding:0 5px;}

/* ── TYPOGRAPHY ── */
h1{
  font-family:'Cormorant Garamond',serif;
  font-size:clamp(2.2rem,7vw,2.8rem);font-weight:300;font-style:italic;
  letter-spacing:0.01em;line-height:1.15;color:var(--white);margin-bottom:14px;
  animation:titleReveal 1.3s cubic-bezier(0.16,1,0.3,1) both;animation-delay:0.15s;
}
@keyframes titleReveal{
  from{opacity:0;transform:translateY(20px);letter-spacing:0.1em;}
  to{opacity:1;transform:translateY(0);}
}
.eyebrow{
  font-family:'DM Mono',monospace;font-size:0.68rem;font-weight:300;
  letter-spacing:0.28em;text-transform:uppercase;color:var(--gold);
  margin-bottom:24px;display:block;opacity:0.85;
  animation:eyebrowReveal 1.1s cubic-bezier(0.16,1,0.3,1) both;
}
@keyframes eyebrowReveal{from{opacity:0;letter-spacing:0.5em}to{opacity:0.85;letter-spacing:0.28em}}
p{
  font-size:0.9rem;font-weight:400;color:var(--text-muted);
  margin-bottom:28px;line-height:2.1;
  animation:fadeUp 1s cubic-bezier(0.16,1,0.3,1) both;animation-delay:0.25s;
}
@keyframes fadeUp{from{opacity:0;transform:translateY(14px)}to{opacity:1;transform:translateY(0)}}

/* ── BUTTONS ── */
.btn{
  display:inline-block;background:transparent;color:var(--gold);
  border:1px solid rgba(160,126,74,0.5);padding:14px 42px;border-radius:2px;
  font-family:'DM Mono',monospace;font-weight:300;font-size:0.7rem;
  letter-spacing:0.26em;text-transform:uppercase;cursor:none;margin-top:20px;
  transition:all 0.5s cubic-bezier(0.34,1.56,0.64,1);position:relative;overflow:hidden;
  outline:none;animation:fadeUp 1s cubic-bezier(0.16,1,0.3,1) both;animation-delay:0.4s;
}
.btn::before{content:'';position:absolute;inset:0;background:linear-gradient(135deg,var(--gold-faint),transparent);opacity:0;transition:opacity 0.4s;}
.btn::after{content:'';position:absolute;top:0;left:-100%;width:60%;height:100%;background:linear-gradient(90deg,transparent,rgba(201,169,110,0.14),transparent);transform:skewX(-20deg);}
.btn:hover::before{opacity:1;}
.btn:hover::after{left:150%;transition:left 0.8s ease;}
.btn:hover{border-color:var(--gold);color:var(--white);box-shadow:0 0 32px var(--gold-faint),0 0 70px rgba(201,169,110,0.07);transform:translateY(-2px);}
.btn:active{transform:scale(0.97) translateY(0);box-shadow:none;}
.btn-ghost{background:transparent!important;border-color:rgba(255,255,255,0.06)!important;color:var(--text-muted)!important;margin-left:12px;box-shadow:none!important;}
.btn-ghost:hover{border-color:rgba(255,255,255,0.1)!important;color:var(--text)!important;transform:none!important;}

/* ── FLIP CARDS ── */
.card-stack{display:flex;flex-direction:column;gap:12px;margin:28px 0;}
.flip-card{height:92px;perspective:2000px;cursor:none;opacity:0;animation:cardReveal 0.8s cubic-bezier(0.16,1,0.3,1) forwards;}
.flip-card:nth-child(1){animation-delay:0.12s;}
.flip-card:nth-child(2){animation-delay:0.28s;}
.flip-card:nth-child(3){animation-delay:0.44s;}
@keyframes cardReveal{from{opacity:0;transform:translateY(24px) rotateX(10deg)}to{opacity:1;transform:translateY(0) rotateX(0)}}
.flip-inner{position:relative;width:100%;height:100%;transition:transform 0.95s cubic-bezier(0.175,0.885,0.32,1.275);transform-style:preserve-3d;}
.flip-card.flipped .flip-inner{transform:rotateY(180deg);}
.front,.back{
  position:absolute;width:100%;height:100%;backface-visibility:hidden;
  -webkit-backface-visibility:hidden;border-radius:3px;
  display:flex;align-items:center;justify-content:center;padding:20px 24px;
  border:1px solid var(--border);transition:border-color 0.3s,box-shadow 0.3s;
}
.front{background:linear-gradient(145deg,var(--surface2),var(--surface3));color:var(--text-muted);font-family:'DM Mono',monospace;font-size:0.68rem;letter-spacing:0.2em;text-transform:uppercase;}
.flip-card:not(.flipped):hover .front{border-color:var(--border-hi);box-shadow:0 4px 24px rgba(0,0,0,0.5);}
.back{background:linear-gradient(145deg,var(--surface3),#1e1a16);border-color:rgba(201,169,110,0.2);transform:rotateY(180deg);color:var(--text);font-family:'Cormorant Garamond',serif;font-size:1.15rem;font-style:italic;font-weight:300;line-height:1.6;box-shadow:0 0 40px rgba(201,169,110,0.07);}

/* ── CAKE ── */
.cake-container{position:relative;display:inline-block;margin:28px 0;}
.cake-hint{font-family:'DM Mono',monospace;font-size:0.6rem;letter-spacing:0.22em;text-transform:uppercase;color:var(--text-dim);margin-top:-16px;margin-bottom:8px;animation:hintPulse 2s ease-in-out infinite;}
@keyframes hintPulse{0%,100%{opacity:0.3}50%{opacity:0.7}}
#cake{
  font-size:clamp(5rem,16vw,6.5rem);cursor:none;
  transition:all 0.4s cubic-bezier(0.34,1.56,0.64,1);display:inline-block;
  filter:drop-shadow(0 0 50px rgba(201,169,110,0.3));
  animation:cakeFloat 4s ease-in-out infinite;will-change:transform;
}
@keyframes cakeFloat{0%,100%{transform:translateY(0) rotate(-1deg)}50%{transform:translateY(-10px) rotate(1deg)}}
#cake:hover{filter:drop-shadow(0 0 70px rgba(201,169,110,0.5));transform:scale(1.08);}
.cake-ring{position:absolute;top:50%;left:50%;width:10px;height:10px;border-radius:50%;border:1px solid var(--gold);transform:translate(-50%,-50%);animation:cakeRing 1s ease-out forwards;pointer-events:none;}
@keyframes cakeRing{from{width:10px;height:10px;opacity:0.9}to{width:140px;height:140px;opacity:0}}

/* ── SLICE ANIMATION ── */
#cakeSlice{
  position:absolute;top:0;left:50%;transform:translateX(-50%);
  width:4px;height:100%;pointer-events:none;
  background:linear-gradient(180deg,var(--gold),transparent);
  opacity:0;transform-origin:top center;
}
#cakeSlice.slicing{animation:sliceAnim 0.3s ease forwards;}
@keyframes sliceAnim{0%{opacity:1;transform:translateX(-50%) scaleY(0)}100%{opacity:0;transform:translateX(-50%) scaleY(1)}}

/* ── JAR ── */
.jar-container{position:relative;margin:24px auto;width:160px;height:200px;display:flex;align-items:center;justify-content:center;}
.jar{
  width:130px;height:168px;
  background:linear-gradient(160deg,rgba(255,255,255,0.05),rgba(255,255,255,0.01));
  border-radius:36px 36px 54px 54px;border:1px solid rgba(255,255,255,0.12);
  position:relative;overflow:hidden;
  box-shadow:0 14px 60px rgba(0,0,0,0.6),inset 0 1px 0 rgba(255,255,255,0.08),inset 2px 0 0 rgba(255,255,255,0.02),0 0 50px rgba(201,169,110,0.05);
  transition:box-shadow 0.5s;
}
.jar::after{content:'';position:absolute;top:10%;left:8%;width:18%;height:58%;background:linear-gradient(180deg,rgba(255,255,255,0.09),transparent);border-radius:50%;pointer-events:none;}
.jar::before{content:'✦';position:absolute;top:14px;left:50%;transform:translateX(-50%);font-size:1.1rem;color:var(--gold);animation:jarGlow 2.5s ease-in-out infinite;z-index:2;}
@keyframes jarGlow{0%,100%{opacity:0.2;text-shadow:none}50%{opacity:1;text-shadow:0 0 18px var(--gold),0 0 35px var(--gold-glow)}}
.golden-orb{position:absolute;border-radius:50%;background:radial-gradient(circle at 30% 30%,#e8c97a,var(--gold-dim));box-shadow:0 0 16px rgba(201,169,110,0.75),0 0 4px rgba(201,169,110,0.4);pointer-events:none;z-index:2;transition:opacity 0.6s;}
#wishIn{
  width:90%;padding:14px 20px;border-radius:2px;border:1px solid var(--border);
  outline:none;font-family:'DM Mono',monospace;font-size:0.82rem;margin:20px 0;
  background:var(--surface2);color:var(--text);letter-spacing:0.06em;
  transition:border-color 0.4s,box-shadow 0.4s;cursor:text;
}
#wishIn::placeholder{color:var(--text-dim);}
#wishIn:focus{border-color:var(--gold-dim);box-shadow:0 0 0 3px rgba(201,169,110,0.07),0 0 24px rgba(201,169,110,0.05);}
.wish-confirm{
  font-family:'DM Mono',monospace;font-size:0.62rem;letter-spacing:0.2em;
  text-transform:uppercase;color:var(--gold);opacity:0;margin-top:-16px;
  transition:opacity 0.5s;
}
.wish-confirm.show{opacity:1;}

/* ── MEMORY LANE ── */
.memory-lane{max-width:100%!important;width:100%!important;padding:0!important;background:var(--surface)!important;overflow-y:auto;-webkit-overflow-scrolling:touch;height:88vh;border-radius:4px!important;}
.memory-header{position:sticky;top:0;background:rgba(8,8,8,0.97);backdrop-filter:blur(28px) saturate(1.3);-webkit-backdrop-filter:blur(28px) saturate(1.3);padding:36px 28px 26px;z-index:100;border-bottom:1px solid var(--border);text-align:center;}
.memory-header h1{margin-bottom:6px;font-size:clamp(1.9rem,6vw,2.2rem);animation:none;}
.memory-subtitle{font-family:'DM Mono',monospace;font-size:0.65rem;letter-spacing:0.24em;text-transform:uppercase;color:var(--text-muted);margin:0;}
.memory-scroll-container{padding:56px 28px 130px;max-width:600px;margin:0 auto;}
.memory-phase{margin-bottom:100px;position:relative;}
.phase-label{font-family:'DM Mono',monospace;font-size:0.65rem;font-weight:300;letter-spacing:0.26em;text-transform:uppercase;color:var(--gold-dim);text-align:center;margin-bottom:56px;position:relative;}
.phase-label::before,.phase-label::after{content:'';position:absolute;top:50%;width:22%;height:1px;}
.phase-label::before{left:0;background:linear-gradient(90deg,transparent,var(--text-dim));}
.phase-label::after{right:0;background:linear-gradient(270deg,transparent,var(--text-dim));}
.memory-item{display:flex;gap:24px;align-items:center;margin-bottom:60px;opacity:0;transform:translateY(40px);transition:opacity 1.4s cubic-bezier(0.16,1,0.3,1),transform 1.4s cubic-bezier(0.16,1,0.3,1);will-change:transform,opacity;}
.memory-item.visible{opacity:1;transform:translateY(0);}

/* Polaroid effect */
.memory-image-wrap{
  flex-shrink:0;width:112px;height:112px;border-radius:2px;
  background:var(--surface3);display:flex;align-items:center;justify-content:center;
  font-size:2.5rem;border:1px solid var(--border);overflow:hidden;
  position:relative;
  filter:brightness(0.6) contrast(1.1) saturate(0.7) sepia(0.15);
  transition:filter 1.8s ease,box-shadow 1.2s ease,transform 0.8s ease;
  box-shadow:0 8px 30px rgba(0,0,0,0.6);
  transform:rotate(var(--tilt,0deg));
}
.memory-item.visible .memory-image-wrap{filter:brightness(0.9) contrast(1.05) saturate(0.9);box-shadow:0 12px 40px rgba(0,0,0,0.5),0 0 0 6px rgba(255,255,255,0.03);}
.memory-image-wrap::before{content:'';position:absolute;inset:0;background:linear-gradient(135deg,rgba(201,169,110,0.06),transparent 50%);pointer-events:none;z-index:1;}
/* Polaroid develop overlay */
.memory-image-wrap::after{content:'';position:absolute;inset:0;background:rgba(255,255,255,0.85);pointer-events:none;z-index:2;transition:opacity 1.6s ease;opacity:1;}
.memory-item.visible .memory-image-wrap::after{opacity:0;}
.memory-image-wrap img{width:100%;height:100%;object-fit:cover;}
.memory-text h3{font-family:'Cormorant Garamond',serif;font-size:1.3rem;font-weight:400;font-style:italic;color:var(--white);margin-bottom:10px;line-height:1.3;}
.memory-text p{font-size:0.87rem;line-height:1.9;color:var(--text-muted);margin:0;animation:none;}
.phase-drift .memory-item.drift-left{margin-right:auto;padding-right:24px;}
.phase-drift .memory-item.drift-right{margin-left:auto;flex-direction:row-reverse;padding-left:24px;}
.phase-now .memory-item.isolated{flex-direction:column;text-align:center;max-width:360px;margin:0 auto 80px;gap:0;}
.phase-now .memory-text.centered{text-align:center;}
.phase-now .memory-text h3{font-size:1.5rem;color:var(--text-muted);}
.phase-now .memory-text p{font-size:0.9rem;color:var(--text-dim);}
.memory-spacer{height:100px;}
.phase-now .memory-item.final .memory-text h3{color:var(--gold);font-size:1.7rem;text-shadow:0 0 40px rgba(201,169,110,0.35);}
.phase-now .memory-item.final .memory-text p{color:var(--text-muted);}

/* ── GAME ── */
#gameArea{
  width:100%;height:260px;
  background:linear-gradient(160deg,var(--surface2),#0c0c0c);
  border-radius:4px;position:relative;overflow:hidden;
  border:1px solid var(--border);margin:20px 0;touch-action:none;cursor:none;
}
#gameArea::after{content:'';position:absolute;inset:0;background:radial-gradient(ellipse at 50% 50%,transparent 50%,rgba(0,0,0,0.5) 100%);pointer-events:none;z-index:3;}
#screenShake{position:absolute;inset:0;z-index:5;pointer-events:none;}
#player,#enemy{position:absolute;width:46px;height:46px;font-size:32px;display:flex;align-items:center;justify-content:center;transform:translate(-50%,-50%);filter:drop-shadow(0 4px 14px rgba(0,0,0,0.7));z-index:2;}
#timer{font-family:'DM Mono',monospace;font-size:0.72rem;letter-spacing:0.24em;text-transform:uppercase;color:var(--gold);margin:10px 0;animation:none;}
#healthBar{width:100%;height:3px;background:rgba(255,255,255,0.05);border-radius:2px;overflow:hidden;margin:8px 0;}
#healthFill{height:100%;background:linear-gradient(90deg,var(--gold-dim),var(--gold));transition:width 0.3s ease;border-radius:2px;box-shadow:0 0 8px var(--gold-glow);}
.game-shake{animation:screenShake 0.35s ease forwards;}
@keyframes screenShake{0%{transform:translate(0)}20%{transform:translate(-5px,3px)}40%{transform:translate(5px,-3px)}60%{transform:translate(-3px,2px)}80%{transform:translate(3px,-2px)}100%{transform:translate(0)}}

/* ── FINAL NOTE ── */
#finalNote{
  text-align:left;line-height:2.1;color:var(--text-muted);
  background:linear-gradient(160deg,var(--surface2),#0c0c0c);
  padding:28px 30px;border-radius:3px;height:320px;overflow-y:auto;
  -webkit-overflow-scrolling:touch;border:1px solid var(--border);margin-top:20px;
  font-family:'Cormorant Garamond',serif;font-size:1.06rem;position:relative;
}
#finalNote::before{content:'"';position:absolute;top:-10px;left:20px;font-size:5.5rem;color:rgba(201,169,110,0.06);font-family:'Cormorant Garamond',serif;line-height:1;pointer-events:none;}
#finalNote::-webkit-scrollbar{width:2px;}
#finalNote::-webkit-scrollbar-track{background:transparent;}
#finalNote::-webkit-scrollbar-thumb{background:var(--gold-dim);border-radius:4px;}
#typedCursor{display:inline-block;width:1px;height:1.1em;background:var(--gold);margin-left:2px;vertical-align:text-bottom;animation:cursorBlink 0.9s ease-in-out infinite;}
@keyframes cursorBlink{0%,100%{opacity:1}50%{opacity:0}}

/* ── GRAND FINALE ── */
#grandFinale{position:fixed;inset:0;z-index:10000;display:none;background:#020202;overflow:hidden;}
#grandFinale.active{display:block;animation:finaleIn 2.5s cubic-bezier(0.16,1,0.3,1) forwards;}
@keyframes finaleIn{from{opacity:0}to{opacity:1}}
#finaleStarCanvas{position:absolute;inset:0;width:100%;height:100%;}
#finaleGlow{position:absolute;width:700px;height:700px;top:50%;left:50%;transform:translate(-50%,-50%);border-radius:50%;background:radial-gradient(circle,rgba(201,169,110,0.07) 0%,transparent 70%);pointer-events:none;animation:finaleGlow 5s ease-in-out infinite;}
@keyframes finaleGlow{0%,100%{opacity:0.6;transform:translate(-50%,-50%) scale(1)}50%{opacity:1;transform:translate(-50%,-50%) scale(1.18)}}
.finale-grain{position:fixed;inset:0;background-image:url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='n'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.85' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23n)' opacity='0.045'/%3E%3C/svg%3E");pointer-events:none;z-index:1;opacity:0.55;}
.finale-message{
  position:absolute;top:50%;left:50%;transform:translate(-50%,-50%);
  width:84%;max-width:600px;text-align:center;opacity:0;
  color:var(--text);font-family:'Cormorant Garamond',serif;
  font-size:clamp(1.2rem,4.5vw,1.6rem);line-height:2.4;font-weight:300;font-style:italic;
  letter-spacing:0.03em;
  transition:opacity 2.2s cubic-bezier(0.16,1,0.3,1),filter 2.2s cubic-bezier(0.16,1,0.3,1),transform 2.2s cubic-bezier(0.16,1,0.3,1);
  filter:blur(12px);transform:translate(-50%,-44%);z-index:10;
}
.finale-message.focus-in{opacity:1;filter:blur(0);transform:translate(-50%,-50%);}
.finale-buttons{position:absolute;bottom:56px;left:50%;transform:translateX(-50%);display:none;gap:16px;opacity:0;flex-wrap:wrap;justify-content:center;z-index:10;}
.finale-buttons.show{display:flex;animation:buttonsAppear 2.2s cubic-bezier(0.16,1,0.3,1) forwards;}
@keyframes buttonsAppear{0%{opacity:0;transform:translateX(-50%) translateY(28px)}100%{opacity:1;transform:translateX(-50%) translateY(0)}}
.finale-btn{
  background:transparent;border:1px solid rgba(201,169,110,0.22);color:var(--gold-dim);
  padding:14px 40px;border-radius:2px;font-family:'DM Mono',monospace;font-size:0.68rem;
  font-weight:300;letter-spacing:0.22em;text-transform:uppercase;cursor:none;
  transition:all 0.5s cubic-bezier(0.16,1,0.3,1);position:relative;overflow:hidden;
}
.finale-btn::before{content:'';position:absolute;inset:0;background:var(--gold-faint);opacity:0;transition:opacity 0.4s;}
.finale-btn:hover::before{opacity:1;}
.finale-btn:hover{border-color:var(--gold);color:var(--white);box-shadow:0 0 32px rgba(201,169,110,0.14);transform:translateY(-2px);}
.finale-btn:active{transform:scale(0.97);}

/* ── LOVE TEXT CANVAS (finale spell-out) ── */
#loveCanvas{position:absolute;inset:0;width:100%;height:100%;z-index:5;pointer-events:none;opacity:0;transition:opacity 2s;}
#loveCanvas.show{opacity:1;}

/* ── RESPONSIVE ── */
@media(max-width:480px){
  .page{padding:40px 24px;}#cake{font-size:4.8rem;}
  .btn{padding:12px 28px;font-size:0.67rem;}
  .finale-message{font-size:1.16rem;line-height:2.2;}
  .finale-buttons{flex-direction:column;gap:12px;bottom:44px;}
  .finale-btn{padding:12px 30px;}.memory-image-wrap{width:92px;height:92px;}
  .btn-ghost{margin-left:0;}
}
@media(max-width:360px){.page{padding:36px 18px;}h1{font-size:2rem;}}
</style>
</head>
<body>

<audio id="bgMusic" loop preload="auto" style="display:none;">
  <source src="https://files.catbox.moe/eui6tr.mp3" type="audio/mpeg">
</audio>

<!-- Cursor -->
<div id="cursor"></div>
<div id="cursor-trail"><canvas id="trailCanvas"></canvas></div>

<!-- Star field -->
<canvas id="starCanvas"></canvas>

<!-- Music -->
<div class="music-control" id="musicControl" onclick="toggleMusic()">
  <span id="musicIcon">♪</span>
</div>

<!-- Progress -->
<div class="progress-container"><div class="progress-bar" id="progressBar"></div></div>

<!-- ── P1: Welcome ── -->
<div id="p1" class="page active">
  <span class="eyebrow">A Gift for You</span>
  <h1>Hello, Junaid Khan.</h1>
  <div class="rule"></div>
  <p>Finally 17 hm?<br><br>Since I can't meet you or hand you something real,<br>I built this just for you.<br><br>I hope it means something.</p>
  <button class="btn" onclick="startMusic();nav('p2')">Open Gift &nbsp;→</button>
</div>

<!-- ── P2: Flip Cards ── -->
<div id="p2" class="page">
  <span class="eyebrow">Little Thoughts</span>
  <h1>For Your Eyes</h1>
  <div class="rule"></div>
  <p>Flip each card — there's something inside.</p>
  <div class="card-stack">
    <div class="flip-card" onclick="flipCard(this)">
      <div class="flip-inner"><div class="front">[ reveal ]</div><div class="back">We fight a lot, but at the end of the day, it's always you ❤️</div></div>
    </div>
    <div class="flip-card" onclick="flipCard(this)">
      <div class="flip-inner"><div class="front">[ reveal ]</div><div class="back">My heart chose you, and it still does… always ❤️</div></div>
    </div>
    <div class="flip-card" onclick="flipCard(this)">
      <div class="flip-inner"><div class="front">[ reveal ]</div><div class="back">Watching you grow makes me so proud 💫.</div></div>
    </div>
  </div>
  <button class="btn" onclick="nav('p3')">Continue &nbsp;→</button>
</div>

<!-- ── P3: Cake ── -->
<div id="p3" class="page">
  <span class="eyebrow">Make a Wish</span>
  <h1>Birthday Cake!!</h1>
  <div class="rule"></div>
  <p>No real cake, but this one's just as special.</p>
  <div class="cake-container" id="cakeContainer">
    <div id="cake" onclick="cut(event)">🎂</div>
    <div id="cakeSlice"></div>
  </div>
  <p class="cake-hint" id="cakeHint">tap to cut</p>
  <div id="cakeBtn" style="display:none">
    <button class="btn" onclick="nav('p4')">Next &nbsp;→</button>
  </div>
</div>

<!-- ── P4: Wishing Jar ── -->
<div id="p4" class="page">
  <span class="eyebrow">Dream Jar</span>
  <h1>Seal a Wish</h1>
  <div class="rule"></div>
  <p>Type a wish. Let the universe hold it.</p>
  <div class="jar-container"><div class="jar" id="jar"></div></div>
  <input type="text" id="wishIn" placeholder="Your wish..." onkeypress="if(event.key==='Enter')addGoldenOrb()">
  <div class="wish-confirm" id="wishConfirm">✦ sealed into the universe ✦</div>
  <button class="btn" onclick="addGoldenOrb()">Send &nbsp;→</button>
  <div id="jarNext" style="display:none;margin-top:20px;">
    <button class="btn" onclick="nav('p5')">Memory Lane &nbsp;→</button>
  </div>
</div>

<!-- ── P5: Memory Lane ── -->
<div id="p5" class="page memory-lane">
  <div class="memory-header">
    <span class="eyebrow" style="display:block;margin-bottom:10px;">A Journey Through Time</span>
    <h1>Memory Lane</h1>
  </div>
  <div class="memory-scroll-container">
    <div class="memory-phase phase-golden">
      <div class="phase-label">Chapter I — The Beginning</div>
      <div class="memory-item" data-phase="golden" style="--tilt:-2deg">
        <div class="memory-image-wrap"><img src="https://files.catbox.moe/9pqd4v.jpeg" alt="When it all started" loading="lazy"></div>
        <div class="memory-text"><h3>When it all started</h3><p>Two strangers who became friends, then best friends, then… something more than words could capture.</p></div>
      </div>
      <div class="memory-item" data-phase="golden" style="--tilt:2deg">
        <div class="memory-text"><h3>The late-night calls</h3><p>Hours would pass like minutes. We'd laugh until our stomachs hurt, share secrets, dream out loud.</p></div>
        <div class="memory-image-wrap"><img src="https://files.catbox.moe/um66hx.jpeg" alt="The late-night calls" loading="lazy"></div>
      </div>
      <div class="memory-item" data-phase="golden" style="--tilt:-1.5deg">
        <div class="memory-image-wrap"><img src="https://files.catbox.moe/w1rvy2.jpeg" alt="Simple contact" loading="lazy"></div>
        <div class="memory-text"><h3>Simple contact</h3><p>When it happened, it happened. When it didn't, that was okay too.</p></div>
      </div>
    </div>
    <div class="memory-phase phase-drift">
      <div class="phase-label">Chapter II — The Distance</div>
      <div class="memory-item drift-left" data-phase="drift" style="--tilt:1.5deg">
        <div class="memory-image-wrap"><img src="https://files.catbox.moe/zwtowy.jpeg" alt="When life got busy" loading="lazy"></div>
        <div class="memory-text"><h3>When life got busy</h3><p>The calls became shorter. The messages less frequent. Not because we cared less… but because time became cruel.</p></div>
      </div>
      <div class="memory-item drift-right" data-phase="drift" style="--tilt:-2deg">
        <div class="memory-text"><h3>Different worlds</h3><p>We started living in parallel universes. Same sky, different stars. So close, yet so far.</p></div>
        <div class="memory-image-wrap"><img src="https://files.catbox.moe/2i5bg3.jpeg" alt="Different worlds" loading="lazy"></div>
      </div>
      <div class="memory-item drift-left" data-phase="drift" style="--tilt:1deg">
        <div class="memory-image-wrap"><img src="https://files.catbox.moe/sli9bk.jpeg" alt="Quiet moments" loading="lazy"></div>
        <div class="memory-text"><h3>Quiet moments</h3><p>A thought would come, and be left there.</p></div>
      </div>
    </div>
    <div class="memory-phase phase-now">
      <div class="phase-label">Chapter III — The Now</div>
      <div class="memory-item isolated" data-phase="now"><div class="memory-text centered"><h3>Miles apart</h3><p>But somehow… we are still here. In every memory that refuses to fade.</p></div></div>
      <div class="memory-spacer"></div>
      <div class="memory-item isolated" data-phase="now"><div class="memory-text centered"><h3>Still caring</h3><p>Even when we don't talk. Even when weeks pass. You matter. You always will.</p></div></div>
      <div class="memory-spacer"></div>
      <div class="memory-item isolated final" data-phase="now"><div class="memory-text centered"><h3>Forever connected</h3><p>Because some bonds don't break with distance. They just… transform. And ours? I'd like to keep it forever.</p></div></div>
    </div>
    <button class="btn" onclick="nav('p6')" style="display:block;margin:0 auto;">Continue &nbsp;→</button>
  </div>
</div>

<!-- ── P6: Game ── -->
<div id="p6" class="page">
  <span class="eyebrow">Challenge</span>
  <h1>Escape</h1>
  <div class="rule"></div>
  <p>Survive for 10 seconds. Move to dodge.</p>
  <div id="gameArea">
    <div id="player" style="left:50%;top:80%;">🧍‍♀️</div>
    <div id="enemy" style="left:20%;top:20%;">😈</div>
  </div>
  <div id="healthBar"><div id="healthFill" style="width:100%"></div></div>
  <p id="timer">Move to start — survive 10s</p>
  <button class="btn btn-ghost" onclick="nav('p7')">Skip →</button>
</div>

<!-- ── P7: Final Note ── -->
<div id="p7" class="page">
  <span class="eyebrow">Final Note</span>
  <h1>A Letter</h1>
  <div class="rule"></div>
  <p>One last thing, written just for you.</p>
  <div id="finalNote"><span id="typed"></span><span id="typedCursor"></span></div>
  <button class="btn" style="letter-spacing:0.22em;margin-top:28px;" onclick="startGrandFinale()">Seal the Journey</button>
</div>

<!-- ── Grand Finale ── -->
<div id="grandFinale">
  <div class="finale-grain"></div>
  <canvas id="finaleStarCanvas"></canvas>
  <div id="finaleGlow"></div>
  <canvas id="loveCanvas"></canvas>
  <div id="finaleMessages"></div>
  <div class="finale-buttons" id="finaleButtons">
    <button class="finale-btn" onclick="finalClose()">Close</button>
    <button class="finale-btn" onclick="resetExperience()">Experience Again</button>
  </div>
</div>

<script>
'use strict';
/* ══════════════════════════════════════════
   CURSOR + TRAIL
══════════════════════════════════════════ */
const cursorEl = document.getElementById('cursor');
const trailCanvas = document.getElementById('trailCanvas');
const trailCtx = trailCanvas.getContext('2d');
let mouseX=0,mouseY=0,cursorX=0,cursorY=0;
let trail=[];
const MAX_TRAIL=60;

function resizeTrail(){trailCanvas.width=window.innerWidth;trailCanvas.height=window.innerHeight;}
resizeTrail();window.addEventListener('resize',resizeTrail);

document.addEventListener('mousemove',e=>{
  mouseX=e.clientX;mouseY=e.clientY;
  cursorEl.style.left=mouseX+'px';cursorEl.style.top=mouseY+'px';
  trail.push({x:mouseX,y:mouseY,age:0,size:4+Math.random()*3,opacity:1});
  if(trail.length>MAX_TRAIL)trail.shift();
});

document.addEventListener('touchmove',e=>{
  const t=e.touches[0];mouseX=t.clientX;mouseY=t.clientY;
  trail.push({x:mouseX,y:mouseY,age:0,size:5,opacity:1});
  if(trail.length>MAX_TRAIL)trail.shift();
},{passive:true});

function animateTrail(){
  trailCtx.clearRect(0,0,trailCanvas.width,trailCanvas.height);
  trail.forEach((p,i)=>{
    p.age+=0.04;
    const life=1-(p.age/1.5);
    if(life<=0){trail.splice(i,1);return;}
    const grd=trailCtx.createRadialGradient(p.x,p.y,0,p.x,p.y,p.size*(1+p.age*0.5));
    grd.addColorStop(0,`rgba(201,169,110,${life*0.55})`);
    grd.addColorStop(0.5,`rgba(201,169,110,${life*0.2})`);
    grd.addColorStop(1,'rgba(201,169,110,0)');
    trailCtx.beginPath();
    trailCtx.arc(p.x,p.y,p.size*(1+p.age*0.5),0,Math.PI*2);
    trailCtx.fillStyle=grd;
    trailCtx.fill();
  });
  requestAnimationFrame(animateTrail);
}
animateTrail();

/* ══════════════════════════════════════════
   STAR FIELD
══════════════════════════════════════════ */
const starCanvas=document.getElementById('starCanvas');
const sctx=starCanvas.getContext('2d');
let stars=[];
function resizeStar(){starCanvas.width=window.innerWidth;starCanvas.height=window.innerHeight;initStars();}
function initStars(){
  stars=[];
  const n=Math.floor(window.innerWidth*window.innerHeight/2800);
  for(let i=0;i<n;i++){
    stars.push({
      x:Math.random()*starCanvas.width,y:Math.random()*starCanvas.height,
      r:Math.random()*1.2+0.2,speed:Math.random()*0.015+0.005,
      phase:Math.random()*Math.PI*2,twinkle:0.3+Math.random()*0.7,
      drift:Math.random()*0.03-0.015
    });
  }
}
resizeStar();window.addEventListener('resize',resizeStar);

let starT=0,starMX=0,starMY=0;
document.addEventListener('mousemove',e=>{starMX=e.clientX-starCanvas.width/2;starMY=e.clientY-starCanvas.height/2;});
function animateStars(){
  sctx.clearRect(0,0,starCanvas.width,starCanvas.height);
  starT+=0.008;
  stars.forEach(s=>{
    s.phase+=s.speed;
    s.x+=s.drift;
    if(s.x<0)s.x=starCanvas.width;
    if(s.x>starCanvas.width)s.x=0;
    const para=0.0003;
    const px=s.x+starMX*para*s.r;const py=s.y+starMY*para*s.r;
    const alpha=s.twinkle*(0.4+0.6*Math.abs(Math.sin(s.phase)));
    const grd=sctx.createRadialGradient(px,py,0,px,py,s.r*2.5);
    const golden=Math.random()>0.7;
    if(golden){grd.addColorStop(0,`rgba(201,169,110,${alpha})`);grd.addColorStop(1,'rgba(201,169,110,0)');}
    else{grd.addColorStop(0,`rgba(240,230,210,${alpha*0.6})`);grd.addColorStop(1,'rgba(240,230,210,0)');}
    sctx.beginPath();sctx.arc(px,py,s.r*2,0,Math.PI*2);sctx.fillStyle=grd;sctx.fill();
  });
  requestAnimationFrame(animateStars);
}
animateStars();

/* ══════════════════════════════════════════
   NAV
══════════════════════════════════════════ */
const totalPages=7;
let currentPage=1,gameInitialized=false,music=null,musicPlaying=false;
let audioUnlocked=false,wishCount=0,firstFlip=false,typingDone=false;

function nav(id){
  if('vibrate' in navigator)navigator.vibrate([6,30,6]);
  const cur=document.querySelector('.page.active');
  const nxt=document.getElementById(id);
  if(!cur||!nxt)return;
  cur.classList.add('exit-stage-1');
  setTimeout(()=>{
    cur.classList.remove('active','exit-stage-1');
    nxt.classList.add('active');
    currentPage=parseInt(id.replace('p',''))||1;
    document.getElementById('progressBar').style.width=(currentPage/totalPages*100)+'%';
    confetti({particleCount:22,spread:60,origin:{y:0.65},colors:['#c9a96e','#a07e4a','#f5f0e8','#e8d9b8'],ticks:110,gravity:1.3,scalar:0.85,drift:0.2});
  },440);
  if(id==='p5')setTimeout(initMemoryLane,550);
  if(id==='p6'&&!gameInitialized)setTimeout(initGame,650);
  if(id==='p7')setTimeout(unwrap,750);
}

/* ══════════════════════════════════════════
   MUSIC
══════════════════════════════════════════ */
function startMusic(){
  if(!music){music=document.getElementById('bgMusic');music.volume=0;}
  if(!audioUnlocked){
    music.play().then(()=>{
      audioUnlocked=true;musicPlaying=true;fadeAudio(music,0,0.3,2200);
      document.getElementById('musicIcon').textContent='♫';
      document.getElementById('musicControl').classList.add('playing');
    }).catch(()=>{});
  }
}
function fadeAudio(el,from,to,dur){
  const steps=50,interval=dur/steps,delta=(to-from)/steps;let step=0;el.volume=from;
  const t=setInterval(()=>{step++;el.volume=Math.max(0,Math.min(1,from+delta*step));if(step>=steps)clearInterval(t);},interval);
}
async function toggleMusic(){
  if(!music){music=document.getElementById('bgMusic');music.volume=0;}
  try{
    if(musicPlaying){
      fadeAudio(music,music.volume,0,700);setTimeout(()=>music.pause(),750);
      document.getElementById('musicIcon').textContent='♪';
      document.getElementById('musicControl').classList.remove('playing');musicPlaying=false;
    }else{
      if(!audioUnlocked){await music.play();audioUnlocked=true;}
      else{music.volume=0;await music.play();}
      fadeAudio(music,0,0.3,1100);
      document.getElementById('musicIcon').textContent='♫';
      document.getElementById('musicControl').classList.add('playing');musicPlaying=true;
    }
  }catch(e){}
}

/* ══════════════════════════════════════════
   FLIP CARDS
══════════════════════════════════════════ */
function flipCard(card){
  card.classList.toggle('flipped');
  if(!firstFlip&&!audioUnlocked){firstFlip=true;setTimeout(()=>startMusic(),400);}
  if(card.classList.contains('flipped')){
    const r=card.getBoundingClientRect();
    confetti({particleCount:20,spread:60,origin:{x:(r.left+r.width/2)/window.innerWidth,y:(r.top+r.height/2)/window.innerHeight},colors:['#c9a96e','#f5f0e8','#e8c97a'],ticks:90,scalar:0.85});
  }
}

/* ══════════════════════════════════════════
   CAKE — SLICE ANIMATION
══════════════════════════════════════════ */
function cut(event){
  const cake=document.getElementById('cake');
  if(cake.textContent==='🍰')return;
  const container=document.getElementById('cakeContainer');
  const ring=document.createElement('div');ring.className='cake-ring';container.appendChild(ring);
  setTimeout(()=>ring.remove(),1100);
  const slice=document.getElementById('cakeSlice');
  slice.classList.add('slicing');setTimeout(()=>slice.classList.remove('slicing'),400);
  cake.style.animation='none';cake.style.transform='scale(1.15)';
  document.getElementById('cakeHint').style.opacity='0';
  setTimeout(()=>{
    cake.textContent='🍰';cake.style.transform='scale(1)';
    cake.style.filter='drop-shadow(0 0 60px rgba(201,169,110,0.55))';
    document.getElementById('cakeBtn').style.display='block';
  },220);
  confetti({particleCount:110,spread:85,origin:{x:0.5,y:0.58},colors:['#c9a96e','#a07e4a','#f5f0e8','#e8d9b8','#ffd700'],ticks:155,gravity:1.1,scalar:0.9});
  if('vibrate' in navigator)navigator.vibrate([15,10,15]);
}

/* ══════════════════════════════════════════
   WISH JAR — PHYSICS ORBS
══════════════════════════════════════════ */
let orbPhysics=[];
function physicsLoop(){
  orbPhysics.forEach(o=>{
    o.vy-=0.015;o.vy*=0.98;o.vx*=0.98;o.x+=o.vx;o.y+=o.vy;
    const maxY=148-o.size/2,minY=36+o.size/2;
    const maxX=120-o.size/2,minX=10+o.size/2;
    if(o.y>maxY){o.y=maxY;o.vy*=-0.45;}
    if(o.y<minY){o.y=minY;o.vy*=-0.45;}
    if(o.x>maxX){o.x=maxX;o.vx*=-0.45;}
    if(o.x<minX){o.x=minX;o.vx*=-0.45;}
    if(o.el){o.el.style.left=o.x+'px';o.el.style.top=o.y+'px';}
  });
  requestAnimationFrame(physicsLoop);
}
physicsLoop();

function addGoldenOrb(){
  const input=document.getElementById('wishIn');
  const wish=input.value.trim();
  if(!wish){input.style.borderColor='rgba(201,169,110,0.5)';setTimeout(()=>input.style.borderColor='',1100);return;}
  const jar=document.getElementById('jar');
  const sizes=[10,8,13,9,12,11,7];
  const size=sizes[wishCount%sizes.length];
  const orb=document.createElement('div');orb.className='golden-orb';
  const startX=55+Math.random()*20;const startY=40;
  orb.style.cssText=`width:${size}px;height:${size}px;left:${startX}px;top:${startY}px;opacity:0;animation:none;transition:opacity 0.5s;`;
  jar.appendChild(orb);
  orbPhysics.push({el:orb,x:startX,y:startY,vx:(Math.random()-0.5)*1.5,vy:1+Math.random(),size});
  requestAnimationFrame(()=>{orb.style.opacity='1';});
  wishCount++;
  const conf=document.getElementById('wishConfirm');
  conf.classList.add('show');setTimeout(()=>conf.classList.remove('show'),2000);
  if(wishCount>=1){
    const jn=document.getElementById('jarNext');jn.style.display='block';
    jn.style.animation='fadeUp 0.8s cubic-bezier(0.16,1,0.3,1) both';
  }
  input.value='';
  confetti({particleCount:12,spread:50,origin:{x:0.5,y:0.52},colors:['#c9a96e','#f5f0e8'],ticks:70,scalar:0.78});
}

/* ══════════════════════════════════════════
   MEMORY LANE — INTERSECTION OBSERVER
══════════════════════════════════════════ */
function initMemoryLane(){
  const observer=new IntersectionObserver(entries=>{
    entries.forEach(e=>{
      if(e.isIntersecting){
        const delay=e.target.dataset.phase==='now'?350:180;
        setTimeout(()=>e.target.classList.add('visible'),delay);
      }
    });
  },{threshold:0.18,rootMargin:'0px 0px -40px 0px'});
  document.querySelectorAll('.memory-item').forEach(item=>observer.observe(item));
}

/* ══════════════════════════════════════════
   GAME — ENEMY AI + SCREEN SHAKE + HEALTH
══════════════════════════════════════════ */
function initGame(){
  if(gameInitialized)return;gameInitialized=true;
  const area=document.getElementById('gameArea');
  const player=document.getElementById('player');
  const enemy=document.getElementById('enemy');
  const healthFill=document.getElementById('healthFill');
  let running=false,startTime=0,health=100,raf=null;
  let px=50,py=80,ex=20,ey=20;
  let ex2=80,ey2=80,showEnemy2=false;

  function shake(){
    area.classList.add('game-shake');
    setTimeout(()=>area.classList.remove('game-shake'),400);
    if('vibrate' in navigator)navigator.vibrate([50,25,50]);
  }

  function tick(t){
    if(!running)return;
    const elapsed=(t-startTime)/1000;
    const left=Math.max(0,10-elapsed);
    const timerEl=document.getElementById('timer');
    timerEl.textContent=`Survive: ${Math.ceil(left)}s`;
    timerEl.style.color=left<4?'#e87a7a':'var(--gold)';

    // Speed ramps up
    const speed=0.55+elapsed*0.055;
    const dx=px-ex,dy=py-ey,dist=Math.sqrt(dx*dx+dy*dy)||1;
    ex+=dx/dist*speed;ey+=dy/dist*speed;
    enemy.style.left=ex+'%';enemy.style.top=ey+'%';

    if(left<=0){
      running=false;
      confetti({particleCount:160,spread:130,origin:{y:0.52},colors:['#c9a96e','#f5f0e8','#ffd700'],ticks:180,gravity:0.85});
      timerEl.textContent='You survived! 🎉';
      setTimeout(()=>nav('p7'),1400);return;
    }

    if(Math.abs(px-ex)<5.5&&Math.abs(py-ey)<5.5){
      health=Math.max(0,health-20);
      healthFill.style.width=health+'%';
      healthFill.style.background=health<40?'linear-gradient(90deg,#e87a7a,#cc4444)':'linear-gradient(90deg,var(--gold-dim),var(--gold))';
      shake();
      // Bounce enemy away
      ex+=Math.sign(ex-px)*12;ey+=Math.sign(ey-py)*12;
      if(health<=0){running=false;timerEl.textContent='Caught — try again';
        setTimeout(()=>{health=100;healthFill.style.width='100%';healthFill.style.background='linear-gradient(90deg,var(--gold-dim),var(--gold))';
          timerEl.style.color='var(--gold)';timerEl.textContent='Move to start — survive 10s';px=50;py=80;ex=20;ey=20;
          player.style.left='50%';player.style.top='80%';enemy.style.left='20%';enemy.style.top='20%';},1800);
        return;
      }
    }
    raf=requestAnimationFrame(tick);
  }

  function move(x,y){
    const rect=area.getBoundingClientRect();
    px=Math.max(4,Math.min(((x-rect.left)/rect.width)*100,96));
    py=Math.max(4,Math.min(((y-rect.top)/rect.height)*100,96));
    player.style.left=px+'%';player.style.top=py+'%';
    if(!running){running=true;startTime=performance.now();raf=requestAnimationFrame(tick);}
  }

  area.addEventListener('mousemove',e=>move(e.clientX,e.clientY));
  area.addEventListener('touchmove',e=>{e.preventDefault();move(e.touches[0].clientX,e.touches[0].clientY);},{passive:false});
}

/* ══════════════════════════════════════════
   TYPEWRITER — smooth natural feel
══════════════════════════════════════════ */
function unwrap(){
  if(typingDone)return;
  const msg=`Happy birthday, my love ❤️\n4 years with you feels so special, from our childhood days to now, we've grown together and that means everything to me.\nI wish I could meet you and celebrate today with you, but even from far away, I'm so excited and happy for you. Distance can't change how much I love you.\nThank you for being my comfort and my happiness. I'm so lucky my childhood love became this beautiful. I love you always 💖`;
  let i=0;
  const typed=document.getElementById('typed');
  const cursor=document.getElementById('typedCursor');
  const note=document.getElementById('finalNote');
  function type(){
    if(i<msg.length){
      const ch=msg.charAt(i);
      if(ch==='\n'){typed.innerHTML+='<br>';}
      else{typed.innerHTML+=ch;}
      i++;
      note.scrollTop=note.scrollHeight;
      const d=ch===','||ch==='.'||ch==='!'?140:(ch===' '?30:32+Math.random()*20);
      setTimeout(type,d);
    }else{typingDone=true;cursor.style.display='none';}
  }
  type();
}

/* ══════════════════════════════════════════
   GRAND FINALE — LOVE TEXT PARTICLE SPELL-OUT
══════════════════════════════════════════ */
let finaleStarCanvas,fsctx,finaleStars=[];
function initFinaleStars(){
  finaleStarCanvas=document.getElementById('finaleStarCanvas');
  fsctx=finaleStarCanvas.getContext('2d');
  finaleStarCanvas.width=window.innerWidth;finaleStarCanvas.height=window.innerHeight;
  finaleStars=[];
  const n=Math.floor(window.innerWidth*window.innerHeight/1800);
  for(let i=0;i<n;i++){
    finaleStars.push({x:Math.random()*finaleStarCanvas.width,y:Math.random()*finaleStarCanvas.height,r:Math.random()*1.5+0.3,phase:Math.random()*Math.PI*2,speed:0.01+Math.random()*0.02});
  }
  animFinaleStars();
}
function animFinaleStars(){
  if(!document.getElementById('grandFinale').classList.contains('active'))return;
  fsctx.clearRect(0,0,finaleStarCanvas.width,finaleStarCanvas.height);
  finaleStars.forEach(s=>{
    s.phase+=s.speed;const a=(0.3+0.7*Math.abs(Math.sin(s.phase)))*0.9;
    const golden=Math.random()>0.65;
    const g=fsctx.createRadialGradient(s.x,s.y,0,s.x,s.y,s.r*2.5);
    if(golden){g.addColorStop(0,`rgba(201,169,110,${a})`);g.addColorStop(1,'rgba(201,169,110,0)');}
    else{g.addColorStop(0,`rgba(245,240,232,${a*0.5})`);g.addColorStop(1,'rgba(245,240,232,0)');}
    fsctx.beginPath();fsctx.arc(s.x,s.y,s.r*2.5,0,Math.PI*2);fsctx.fillStyle=g;fsctx.fill();
  });
  requestAnimationFrame(animFinaleStars);
}

// "I love you" particle spell-out
function spellLoveYou(){
  const lc=document.getElementById('loveCanvas');
  lc.width=window.innerWidth;lc.height=window.innerHeight;
  lc.classList.add('show');
  const lctx=lc.getContext('2d');
  const W=lc.width,H=lc.height;
  // Draw text offscreen to get pixel positions
  const offscreen=document.createElement('canvas');
  const fontSize=Math.min(W*0.13,90);
  offscreen.width=W;offscreen.height=H;
  const octx=offscreen.getContext('2d');
  octx.fillStyle='#fff';
  octx.font=`300 italic ${fontSize}px "Cormorant Garamond",serif`;
  octx.textAlign='center';octx.textBaseline='middle';
  octx.fillText('I love you ❤️',W/2,H/2);
  const data=octx.getImageData(0,0,W,H).data;
  let pts=[];
  const step=Math.max(4,Math.floor(W/100));
  for(let y=0;y<H;y+=step){
    for(let x=0;x<W;x+=step){
      const idx=(y*W+x)*4;
      if(data[idx+3]>128)pts.push({tx:x,ty:y,x:Math.random()*W,y:Math.random()*H,vx:0,vy:0,done:false,r:Math.random()*2+1,c:Math.random()>0.4?`rgba(201,169,110,${0.7+Math.random()*0.3})`:`rgba(245,240,232,${0.5+Math.random()*0.5})`});
    }
  }
  let t=0;
  function anim(){
    lctx.clearRect(0,0,W,H);
    let allDone=true;
    pts.forEach(p=>{
      const dx=p.tx-p.x,dy=p.ty-p.y;
      p.vx+=dx*0.07;p.vy+=dy*0.07;p.vx*=0.78;p.vy*=0.78;
      p.x+=p.vx;p.y+=p.vy;
      if(Math.abs(dx)>1||Math.abs(dy)>1)allDone=false;
      const g=lctx.createRadialGradient(p.x,p.y,0,p.x,p.y,p.r*2);
      g.addColorStop(0,p.c);g.addColorStop(1,'transparent');
      lctx.beginPath();lctx.arc(p.x,p.y,p.r*2,0,Math.PI*2);lctx.fillStyle=g;lctx.fill();
    });
    t++;
    if(!allDone||t<120)requestAnimationFrame(anim);
  }
  anim();
}

function startGrandFinale(){
  const page=document.getElementById('p7');
  page.classList.add('exit-stage-1');
  if(music&&musicPlaying)fadeAudio(music,music.volume,0,2500);
  setTimeout(()=>{
    page.style.display='none';
    const finale=document.getElementById('grandFinale');
    finale.classList.add('active');
    initFinaleStars();
    const messages=[
      "2139+ lines of code. Hundreds of errors. Countless hours of debugging. I hope all this effort made you smile, even just for a moment.",
      "If it did, every single hour building this was worth it. I don't care how hard it was.",
      "Thank you, Junaid khan for being exactly who you are. You mean a lot to me.",
      "I hope this little experience made you feel special, because you truly are. Happy 17th birthday, my love. Here's to many more years of memories together. I love you ❤️",
      "I love you ❤️"
    ];
    showMessagesSequentially(messages);
  },950);
}

async function showMessagesSequentially(messages){
  const container=document.getElementById('finaleMessages');
  for(let i=0;i<messages.length;i++){
    container.innerHTML='';
    const d=document.createElement('div');d.className='finale-message';d.textContent=messages[i];container.appendChild(d);
    await new Promise(r=>setTimeout(r,130));d.classList.add('focus-in');
    const dt=i===0?7200:(i===messages.length-1?5000:5500);
    await new Promise(r=>setTimeout(r,dt));
    d.classList.remove('focus-in');
    await new Promise(r=>setTimeout(r,1400));
  }
  // Particle love text
  container.innerHTML='';
  spellLoveYou();
  setTimeout(()=>{
    document.getElementById('finaleButtons').classList.add('show');
    setTimeout(()=>{
      confetti({particleCount:80,spread:110,origin:{y:0.28},colors:['#c9a96e','#f5f0e8','#a07e4a'],ticks:220,gravity:0.55,scalar:0.95,drift:0.6});
    },600);
  },2000);
}

function finalClose(){
  if(music){fadeAudio(music,music.volume,0,900);setTimeout(()=>music.pause(),960);}
  setTimeout(()=>window.close(),1000);
}
function resetExperience(){location.reload();}

/* ══════════════════════════════════════════
   INIT
══════════════════════════════════════════ */
document.addEventListener('DOMContentLoaded',()=>{
  music=document.getElementById('bgMusic');music.volume=0;
  document.getElementById('progressBar').style.width=(1/totalPages*100)+'%';
  // Preload images
  ['9pqd4v','um66hx','w1rvy2','zwtowy','2i5bg3','sli9bk'].forEach(id=>{const img=new Image();img.src=`https://files.catbox.moe/${id}.jpeg`;});
});
</script>
</body>
</html>
