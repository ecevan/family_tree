``` mermaid
        flowchart TD
          classDef verticalTextClass text-orientation: upright, writing-mode: vertical-lr, height: 80px;
          classDef deg90 rotate: 90deg;
          subgraph LGTOYC[" "]
            direction LR
            LGT_life[农 1911-11-4 <br> 1995-12-30 卒] -.- gen_1[<h1>罗桂腾 区艳春</h1>] -.- OYC_life[农 1911-11-4 <br> 1995-12-30 卒];
          end
          subgraph gen_2[" "]
            subgraph LJYGBB[" "]
            direction TB
            LJY[<h2>罗<br>建<br>猷</h2>] -.- LJY_life[农 1942-06-26<br><p></p>]:::deg90
            GBB[<h2>古<br>斌<br>斌</h2>] -.- GBB_life[农 1942-11-05<br>1995-07-27 卒]:::deg90
            end
          end
          subgraph gen_3[" "]
              subgraph CRMLWL[" "]
                direction TB
                CRM[<h3>陈<br>汝<br>明</h3>] -.- CRM_life[1965-11-04<br><p></p>]:::deg90
                LWL[<h3>罗<br>蔚<br>铃</h3>] -.- LWL_life[1971-12-19<br><p></p>]:::deg90
              end
              subgraph XZYLJE[" "]
                direction TB
                XZY[<h3>许<br>哲<br>源</h3>] -.- XZY_life[Geoffery<br>1960-05<br><p></p>]:::deg90
                LJE[<h3>罗<br>嘉<br>恩</h3>] -.- LJE_life[Janette<br>1981-02<br><p></p>]:::deg90
              end
              subgraph LTLTati[" "]
                direction TB
                LTL[<h3>罗<br>天<br>乐</h3>] -.- LTL_life[Taylor<br>1960-05<br><p></p>]:::deg90
                Tati[<h3>T<br>a<br>t<br>i</h3>] -.- Tati_life[1981-02<br><p></p>]:::deg90
              end
              subgraph LHJLTN[" "]
                direction TB
                LHJ[<h3>李<br>鸿<br>基</h3>] -.- LHJ_life[Brian<br>1986-03<br><p></p>]:::deg90
                LTN[<h3>罗<br>天<br>宁</h3>] -.- LTN_life[Lian<br>1991-12<br><p></p>]:::deg90
              end
              subgraph LtL[" "]
                direction TB
                LtL1[<h3>罗<br>天<br>伦</h3>] -.- LtL1_life[Alan<br>1993-01<br><p></p>]:::deg90
              end
          end
          subgraph gen_4[" "]
              subgraph CYJHJQ[" "]
                direction TB
                CYJ[<h4>陈<br>炎<br>佳</h4>] -.- CYJ_life[Evan<br>1994-01-17<br><p></p>]:::deg90
                HJQ[<h4>何<br>加<br>琪</h4>] -.- HJQ_life[Kay<br>1993-10-12<br><p></p>]:::deg90
              end
              subgraph CYJ_fam[" "]
                direction TB
                CyJ[<h4>陈<br>怡<br>君</h4>] -.- CYJ1_life[Sophia<br>2016-10<br><p></p>]:::deg90
              end
              subgraph XJH_fam[" "]
                direction TB
                XJH[<h4>许<br>景<br>皓</h4>] -.- XJH_life[Herald<br>2010<br><p></p>]:::deg90
              end
              subgraph XJC_fam[" "]
                direction TB
                XJC[<h4>许<br>景<br>程</h4>] -.- XJC_life[Irwin<br>2010<br><p></p>]:::deg90
              end
              subgraph XJX_fam[" "]
                direction TB
                XJX[<h4>许<br>景<br>翔</h4>] -.- XJX_life[Jon<br>2015<br><p></p>]:::deg90
              end

          end


          LGTOYC --- LJYGBB
          LJYGBB --- CRMLWL
          LJYGBB --- XZYLJE
          CRMLWL --- CYJHJQ
          CRMLWL --- CYJ_fam
          XZYLJE --- XJH_fam
          XZYLJE --- XJC_fam
          XZYLJE --- XJX_fam
```
