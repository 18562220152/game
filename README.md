<html>
    <html lang="zh">
    <head>
        <meta charset="utf-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge,chrome=1">
        <meta http-equiv="x-dns-prefetch-control" content="on" />
        <link rel="dns-prefetch" href="https://qzonestyle.gtimg.cn">
        <link rel="dns-prefetch" href="https://apphub.qzone.qq.com">
        <title>猎鱼达人</title>
        <meta name="keywords" content="猎鱼达人,网页游戏,游戏应用中心">
        <meta name="description" content="">
        <style type="text/css">
        html{width:100%; height:100%;}
        body{width:100%; height:100%;}
        </style>
        <style>
            .forbiddenRealname {
                position: fixed;
                z-index: 99;
                top: 0;
                left: 0;
                width: 100%;
                height: 100%;
                background: rgba(0,0,0,.6);
            }
            .inner {
                position: absolute;
                width: 450px;
                height: 150px;
                /*  固定宽高第一种居中  */
                top: 50%;
                left: 50%;
                margin-left: -225px;
                margin-top: -75px;
                /*  固定宽高第二种居中
                top: 0;
                left: 0;
                right: 0;
                bottom: 0;
                margin: auto;
                */
            }
            .realNameTips {
                width: 100%;
                height: 100%;
            }
            .goRealName {
                position: absolute;
                right: 175px;
                bottom: 15px;
                cursor: pointer
            }
        </style>
        <script>
        var locHref = location.href;
        if(locHref.indexOf('QZSTORE.V6.MY-APPS') >= 0 ||  locHref.indexOf('QZSTORE.V6.MY-APPS-') >= 0 ||  locHref.indexOf('QZ.CANVAS.TOP-') >= 0 || locHref.indexOf('CANVAS.MY-APPS') >= 0){
            var forceViaHref = locHref.replace('QZSTORE.V6.MY-APPS-', 'QZSTORE.V6.MY.APPS.').replace('QZSTORE.V6.MY-APPS', 'QZSTORE.V6.MY.APPS').replace('QZ.CANVAS.TOP-', 'QZ.CANVAS.TOP.').replace('CANVAS.MY-APPS', 'CANVAS.MY.APPS');
            location.href = forceViaHref;
        }
    
        if(window.location.search.match(/loginFromAppcenter=\d+/)){
                var userClickTime = window.location.search.match(/loginFromAppcenter=\d+/)[0];
                window._reporterTime = {
                    baseTime:userClickTime
                };
                }else{
                    window._reporterTime = {
                    baseTime:new Date().getTime()
                };
    }
        </script>        <link rel="stylesheet" type="text/css" href="https://h5.qzone.qq.com/proxy/domain/qzonestyle.gtimg.cn/touch/proj-qzone-app/application-v3/page-pc-popup.css?max_age=2592000" />            <script>
            window.document.domain = 'qq.com';
            window._reporterTime.cssReady = new Date().getTime();
            window.productsCache = {};
            window.productInfo = {
                name: 'Canvas Page',
                id: '6bba8142-5a24-4336-9254-bcaa2ae90be8'
            };
            window.reportPathname = '/game/canvas';
        </script>
    
    <script>
            window.TempstatLast = window.localStorage.getItem('start');
            window.TempendLast = window.localStorage.getItem('end');
            window.localStorage.setItem('start',(new Date()).getTime());
    </script>
    
    
    </head>
    <body data-via="H5.QZONE.PC">            <div class="minigame-platform">
            <div class="fusion_dialog_header">
                <a href="https://game.qzone.qq.com" class="appstore" target="_blank">游戏中心</a>
                <button title="关闭" id="j_close"></button>
                <div class="gb-hrefs">
                    <div class="gb-bar-btn">
                        <div class="fusion__phonetips in-top" id="J_bubble_btn" data-hot-button="CANVAS.GAME.SAVETOQQ">
                            <div class="fusion__btn-phone">
                                <i class="gb-ico gb-ico-phone"></i>
                                <a href="javascript:void(0);">手Q扫一扫直接玩</a>
                            </div>
                            <div class="fusion__qcode-popup">
                                <!-- 二维码尺寸 224x224 -->    <div>
        <div id="j-qrcode-con" style="width:230px;height:230px;margin: 0 auto;margin-top: 10px;display:block"></div>
    </div>
    <script>
        var qrcode = function (a) {
        var appid  = location.pathname.split('/').pop();
        var d = 'https://h5.qzone.qq.com/app/open/'+appid+'/home?_proxy=1&_wv=145191&via=H5.QZONE.PCQRCODE';
        var b = document.createElement("canvas").getContext ? "canvas" : "table",

            c = QRErrorCorrectLevel.H, e = function () {
                var a = new QRCode(-1, c);
                a.addData(d);
                a.make();
                var b = document.createElement("table");
                b.style.width = "220px";
                b.style.height = "220px";
                b.style.border = "0px";
                b.style.backgroundColor = "#ffffff";
                b.style.borderCollapse = "collapse";
                for (var e = 220 / a.getModuleCount(), k = 220 / a.getModuleCount(), m = 0; m < a.getModuleCount(); m++) {
                    var h = document.createElement("tr");
                    h.style.height = k + "px";
                    b.appendChild(h);
                    for (var n = 0; n < a.getModuleCount(); n++) {
                        var p = document.createElement("td");
                        p.style.width = e + "px";
                        p.style.backgroundColor = a.isDark(m, n) ? "#000000" : "#ffffff";
                        h.appendChild(p)
                    }
                }
                return b
            },
            b = "canvas" == b ? function () {
                var a = new QRCode(-1, c);
                a.addData(d);
                a.make();
                var b = document.createElement("canvas");
                b.width = 220;
                b.height = 220;
                for (var e = b.getContext("2d"), k = 220 / a.getModuleCount(), m = 220 / a.getModuleCount(), h = 0; h < a.getModuleCount(); h++) for (var n = 0; n < a.getModuleCount(); n++) e.fillStyle = a.isDark(h, n) ?
                    "#000000" : "#ffffff", e.fillRect(Math.round(n * k), Math.round(h * m), Math.ceil((n + 1) * k) - Math.floor(n * k), Math.ceil((h + 1) * k) - Math.floor(h * k));
                return b
            }() : e();
        a.appendChild(b)
    };

    function QR8bitByte(a) {
        this.mode = QRMode.MODE_8BIT_BYTE;
        this.data = a
    }

    QR8bitByte.prototype = {
        getLength: function (a) {
            return this.data.length
        }, write: function (a) {
            for (var b = 0; b < this.data.length; b++) a.put(this.data.charCodeAt(b), 8)
        }
    };

    function QRCode(a, b) {
        this.typeNumber = a;
        this.errorCorrectLevel = b;
        this.modules = null;
        this.moduleCount = 0;
        this.dataCache = null;
        this.dataList = []
    }

    QRCode.prototype = {
        addData: function (a) {
            a = new QR8bitByte(a);
            this.dataList.push(a);
            this.dataCache = null
        }, isDark: function (a, b) {
            if (0 > a || this.moduleCount <= a || 0 > b || this.moduleCount <= b) throw Error(a + "," + b);
            return this.modules[a][b]
        }, getModuleCount: function () {
            return this.moduleCount
        }, make: function () {
            if (1 > this.typeNumber) {
                for (var a = 1, a = 1; 40 > a; a++) {
                    for (var b = QRRSBlock.getRSBlocks(a, this.errorCorrectLevel), d = new QRBitBuffer, c = 0, e = 0; e < b.length; e++) c += b[e].dataCount;
                    for (e = 0; e < this.dataList.length; e++) b = this.dataList[e],
                        d.put(b.mode, 4), d.put(b.getLength(), QRUtil.getLengthInBits(b.mode, a)), b.write(d);
                    if (d.getLengthInBits() <= 8 * c) break
                }
                this.typeNumber = a
            }
            this.makeImpl(!1, this.getBestMaskPattern())
        }, makeImpl: function (a, b) {
            this.moduleCount = 4 * this.typeNumber + 17;
            this.modules = Array(this.moduleCount);
            for (var d = 0; d < this.moduleCount; d++) {
                this.modules[d] = Array(this.moduleCount);
                for (var c = 0; c < this.moduleCount; c++) this.modules[d][c] = null
            }
            this.setupPositionProbePattern(0, 0);
            this.setupPositionProbePattern(this.moduleCount - 7, 0);
            this.setupPositionProbePattern(0,
                this.moduleCount - 7);
            this.setupPositionAdjustPattern();
            this.setupTimingPattern();
            this.setupTypeInfo(a, b);
            7 <= this.typeNumber && this.setupTypeNumber(a);
            null == this.dataCache && (this.dataCache = QRCode.createData(this.typeNumber, this.errorCorrectLevel, this.dataList));
            this.mapData(this.dataCache, b)
        }, setupPositionProbePattern: function (a, b) {
            for (var d = -1; 7 >= d; d++) if (!(-1 >= a + d || this.moduleCount <= a + d)) for (var c = -1; 7 >= c; c++) -1 >= b + c || this.moduleCount <= b + c || (this.modules[a + d][b + c] = 0 <= d && 6 >= d && (0 == c || 6 == c) || 0 <= c && 6 >=
            c && (0 == d || 6 == d) || 2 <= d && 4 >= d && 2 <= c && 4 >= c ? !0 : !1)
        }, getBestMaskPattern: function () {
            for (var a = 0, b = 0, d = 0; 8 > d; d++) {
                this.makeImpl(!0, d);
                var c = QRUtil.getLostPoint(this);
                if (0 == d || a > c) a = c, b = d
            }
            return b
        }, createMovieClip: function (a, b, d) {
            a = a.createEmptyMovieClip(b, d);
            this.make();
            for (b = 0; b < this.modules.length; b++) {
                d = 1 * b;
                for (var c = 0; c < this.modules[b].length; c++) {
                    var e = 1 * c;
                    this.modules[b][c] && (a.beginFill(0, 100), a.moveTo(e, d), a.lineTo(e + 1, d), a.lineTo(e + 1, d + 1), a.lineTo(e, d + 1), a.endFill())
                }
            }
            return a
        }, setupTimingPattern: function () {
            for (var a =
                8; a < this.moduleCount - 8; a++) null == this.modules[a][6] && (this.modules[a][6] = 0 == a % 2);
            for (a = 8; a < this.moduleCount - 8; a++) null == this.modules[6][a] && (this.modules[6][a] = 0 == a % 2)
        }, setupPositionAdjustPattern: function () {
            for (var a = QRUtil.getPatternPosition(this.typeNumber), b = 0; b < a.length; b++) for (var d = 0; d < a.length; d++) {
                var c = a[b], e = a[d];
                if (null == this.modules[c][e]) for (var f = -2; 2 >= f; f++) for (var l = -2; 2 >= l; l++) this.modules[c + f][e + l] = -2 == f || 2 == f || -2 == l || 2 == l || 0 == f && 0 == l ? !0 : !1
            }
        }, setupTypeNumber: function (a) {
            for (var b =
                QRUtil.getBCHTypeNumber(this.typeNumber), d = 0; 18 > d; d++) {
                var c = !a && 1 == (b >> d & 1);
                this.modules[Math.floor(d / 3)][d % 3 + this.moduleCount - 8 - 3] = c
            }
            for (d = 0; 18 > d; d++) c = !a && 1 == (b >> d & 1), this.modules[d % 3 + this.moduleCount - 8 - 3][Math.floor(d / 3)] = c
        }, setupTypeInfo: function (a, b) {
            for (var d = QRUtil.getBCHTypeInfo(this.errorCorrectLevel << 3 | b), c = 0; 15 > c; c++) {
                var e = !a && 1 == (d >> c & 1);
                6 > c ? this.modules[c][8] = e : 8 > c ? this.modules[c + 1][8] = e : this.modules[this.moduleCount - 15 + c][8] = e
            }
            for (c = 0; 15 > c; c++) e = !a && 1 == (d >> c & 1), 8 > c ? this.modules[8][this.moduleCount -
            c - 1] = e : 9 > c ? this.modules[8][15 - c - 1 + 1] = e : this.modules[8][15 - c - 1] = e;
            this.modules[this.moduleCount - 8][8] = !a
        }, mapData: function (a, b) {
            for (var d = -1, c = this.moduleCount - 1, e = 7, f = 0, l = this.moduleCount - 1; 0 < l; l -= 2) for (6 == l && l--; ;) {
                for (var g = 0; 2 > g; g++) if (null == this.modules[c][l - g]) {
                    var k = !1;
                    f < a.length && (k = 1 == (a[f] >>> e & 1));
                    QRUtil.getMask(b, c, l - g) && (k = !k);
                    this.modules[c][l - g] = k;
                    e--;
                    -1 == e && (f++, e = 7)
                }
                c += d;
                if (0 > c || this.moduleCount <= c) {
                    c -= d;
                    d = -d;
                    break
                }
            }
        }
    };
    QRCode.PAD0 = 236;
    QRCode.PAD1 = 17;
    QRCode.createData = function (a, b, d) {
        b = QRRSBlock.getRSBlocks(a, b);
        for (var c = new QRBitBuffer, e = 0; e < d.length; e++) {
            var f = d[e];
            c.put(f.mode, 4);
            c.put(f.getLength(), QRUtil.getLengthInBits(f.mode, a));
            f.write(c)
        }
        for (e = a = 0; e < b.length; e++) a += b[e].dataCount;
        if (c.getLengthInBits() > 8 * a) throw Error("code length overflow. (" + c.getLengthInBits() + ">" + 8 * a + ")");
        for (c.getLengthInBits() + 4 <= 8 * a && c.put(0, 4); 0 != c.getLengthInBits() % 8;) c.putBit(!1);
        for (; !(c.getLengthInBits() >= 8 * a);) {
            c.put(QRCode.PAD0, 8);
            if (c.getLengthInBits() >=
                8 * a) break;
            c.put(QRCode.PAD1, 8)
        }
        return QRCode.createBytes(c, b)
    };
    QRCode.createBytes = function (a, b) {
        for (var d = 0, c = 0, e = 0, f = Array(b.length), l = Array(b.length), g = 0; g < b.length; g++) {
            var k = b[g].dataCount, m = b[g].totalCount - k, c = Math.max(c, k), e = Math.max(e, m);
            f[g] = Array(k);
            for (var h = 0; h < f[g].length; h++) f[g][h] = 255 & a.buffer[h + d];
            d += k;
            h = QRUtil.getErrorCorrectPolynomial(m);
            k = (new QRPolynomial(f[g], h.getLength() - 1)).mod(h);
            l[g] = Array(h.getLength() - 1);
            for (h = 0; h < l[g].length; h++) m = h + k.getLength() - l[g].length, l[g][h] = 0 <= m ? k.get(m) : 0
        }
        for (h = g = 0; h < b.length; h++) g += b[h].totalCount;
        d = Array(g);
        for (h = k = 0; h < c; h++) for (g = 0; g < b.length; g++) h < f[g].length && (d[k++] = f[g][h]);
        for (h = 0; h < e; h++) for (g = 0; g < b.length; g++) h < l[g].length && (d[k++] = l[g][h]);
        return d
    };
    for (var QRMode = {
        MODE_NUMBER: 1,
        MODE_ALPHA_NUM: 2,
        MODE_8BIT_BYTE: 4,
        MODE_KANJI: 8
    }, QRErrorCorrectLevel = {L: 1, M: 0, Q: 3, H: 2}, QRMaskPattern = {
        PATTERN000: 0,
        PATTERN001: 1,
        PATTERN010: 2,
        PATTERN011: 3,
        PATTERN100: 4,
        PATTERN101: 5,
        PATTERN110: 6,
        PATTERN111: 7
    }, QRUtil = {
        PATTERN_POSITION_TABLE: [[], [6, 18], [6, 22], [6, 26], [6, 30], [6, 34], [6, 22, 38], [6, 24, 42], [6, 26, 46], [6, 28, 50], [6, 30, 54], [6, 32, 58], [6, 34, 62], [6, 26, 46, 66], [6, 26, 48, 70], [6, 26, 50, 74], [6, 30, 54, 78], [6, 30, 56, 82], [6, 30, 58, 86], [6, 34, 62, 90], [6, 28, 50, 72, 94], [6, 26, 50, 74, 98], [6,
            30, 54, 78, 102], [6, 28, 54, 80, 106], [6, 32, 58, 84, 110], [6, 30, 58, 86, 114], [6, 34, 62, 90, 118], [6, 26, 50, 74, 98, 122], [6, 30, 54, 78, 102, 126], [6, 26, 52, 78, 104, 130], [6, 30, 56, 82, 108, 134], [6, 34, 60, 86, 112, 138], [6, 30, 58, 86, 114, 142], [6, 34, 62, 90, 118, 146], [6, 30, 54, 78, 102, 126, 150], [6, 24, 50, 76, 102, 128, 154], [6, 28, 54, 80, 106, 132, 158], [6, 32, 58, 84, 110, 136, 162], [6, 26, 54, 82, 110, 138, 166], [6, 30, 58, 86, 114, 142, 170]],
        G15: 1335,
        G18: 7973,
        G15_MASK: 21522,
        getBCHTypeInfo: function (a) {
            for (var b = a << 10; 0 <= QRUtil.getBCHDigit(b) - QRUtil.getBCHDigit(QRUtil.G15);) b ^=
                QRUtil.G15 << QRUtil.getBCHDigit(b) - QRUtil.getBCHDigit(QRUtil.G15);
            return (a << 10 | b) ^ QRUtil.G15_MASK
        },
        getBCHTypeNumber: function (a) {
            for (var b = a << 12; 0 <= QRUtil.getBCHDigit(b) - QRUtil.getBCHDigit(QRUtil.G18);) b ^= QRUtil.G18 << QRUtil.getBCHDigit(b) - QRUtil.getBCHDigit(QRUtil.G18);
            return a << 12 | b
        },
        getBCHDigit: function (a) {
            for (var b = 0; 0 != a;) b++, a >>>= 1;
            return b
        },
        getPatternPosition: function (a) {
            return QRUtil.PATTERN_POSITION_TABLE[a - 1]
        },
        getMask: function (a, b, d) {
            switch (a) {
                case QRMaskPattern.PATTERN000:
                    return 0 == (b + d) %
                        2;
                case QRMaskPattern.PATTERN001:
                    return 0 == b % 2;
                case QRMaskPattern.PATTERN010:
                    return 0 == d % 3;
                case QRMaskPattern.PATTERN011:
                    return 0 == (b + d) % 3;
                case QRMaskPattern.PATTERN100:
                    return 0 == (Math.floor(b / 2) + Math.floor(d / 3)) % 2;
                case QRMaskPattern.PATTERN101:
                    return 0 == b * d % 2 + b * d % 3;
                case QRMaskPattern.PATTERN110:
                    return 0 == (b * d % 2 + b * d % 3) % 2;
                case QRMaskPattern.PATTERN111:
                    return 0 == (b * d % 3 + (b + d) % 2) % 2;
                default:
                    throw Error("bad maskPattern:" + a);
            }
        },
        getErrorCorrectPolynomial: function (a) {
            for (var b = new QRPolynomial([1], 0), d = 0; d <
            a; d++) b = b.multiply(new QRPolynomial([1, QRMath.gexp(d)], 0));
            return b
        },
        getLengthInBits: function (a, b) {
            if (1 <= b && 10 > b) switch (a) {
                case QRMode.MODE_NUMBER:
                    return 10;
                case QRMode.MODE_ALPHA_NUM:
                    return 9;
                case QRMode.MODE_8BIT_BYTE:
                    return 8;
                case QRMode.MODE_KANJI:
                    return 8;
                default:
                    throw Error("mode:" + a);
            } else if (27 > b) switch (a) {
                case QRMode.MODE_NUMBER:
                    return 12;
                case QRMode.MODE_ALPHA_NUM:
                    return 11;
                case QRMode.MODE_8BIT_BYTE:
                    return 16;
                case QRMode.MODE_KANJI:
                    return 10;
                default:
                    throw Error("mode:" + a);
            } else if (41 > b) switch (a) {
                case QRMode.MODE_NUMBER:
                    return 14;
                case QRMode.MODE_ALPHA_NUM:
                    return 13;
                case QRMode.MODE_8BIT_BYTE:
                    return 16;
                case QRMode.MODE_KANJI:
                    return 12;
                default:
                    throw Error("mode:" + a);
            } else throw Error("type:" + b);
        },
        getLostPoint: function (a) {
            for (var b = a.getModuleCount(), d = 0, c = 0; c < b; c++) for (var e = 0; e < b; e++) {
                for (var f = 0, l = a.isDark(c, e), g = -1; 1 >= g; g++) if (!(0 > c + g || b <= c + g)) for (var k = -1; 1 >= k; k++) 0 > e + k || b <= e + k || 0 == g && 0 == k || l != a.isDark(c + g, e + k) || f++;
                5 < f && (d += 3 + f - 5)
            }
            for (c = 0; c < b - 1; c++) for (e = 0; e < b - 1; e++) if (f = 0, a.isDark(c, e) && f++, a.isDark(c + 1, e) && f++, a.isDark(c,
                    e + 1) && f++, a.isDark(c + 1, e + 1) && f++, 0 == f || 4 == f) d += 3;
            for (c = 0; c < b; c++) for (e = 0; e < b - 6; e++) a.isDark(c, e) && !a.isDark(c, e + 1) && a.isDark(c, e + 2) && a.isDark(c, e + 3) && a.isDark(c, e + 4) && !a.isDark(c, e + 5) && a.isDark(c, e + 6) && (d += 40);
            for (e = 0; e < b; e++) for (c = 0; c < b - 6; c++) a.isDark(c, e) && !a.isDark(c + 1, e) && a.isDark(c + 2, e) && a.isDark(c + 3, e) && a.isDark(c + 4, e) && !a.isDark(c + 5, e) && a.isDark(c + 6, e) && (d += 40);
            for (e = f = 0; e < b; e++) for (c = 0; c < b; c++) a.isDark(c, e) && f++;
            return d += Math.abs(100 * f / b / b - 50) / 5 * 10
        }
    }, QRMath = {
        glog: function (a) {
            if (1 > a) throw Error("glog(" +
                a + ")");
            return QRMath.LOG_TABLE[a]
        }, gexp: function (a) {
            for (; 0 > a;) a += 255;
            for (; 256 <= a;) a -= 255;
            return QRMath.EXP_TABLE[a]
        }, EXP_TABLE: Array(256), LOG_TABLE: Array(256)
    }, i = 0; 8 > i; i++) QRMath.EXP_TABLE[i] = 1 << i;
    for (i = 8; 256 > i; i++) QRMath.EXP_TABLE[i] = QRMath.EXP_TABLE[i - 4] ^ QRMath.EXP_TABLE[i - 5] ^ QRMath.EXP_TABLE[i - 6] ^ QRMath.EXP_TABLE[i - 8];
    for (i = 0; 255 > i; i++) QRMath.LOG_TABLE[QRMath.EXP_TABLE[i]] = i;

    function QRPolynomial(a, b) {
        if (void 0 == a.length) throw Error(a.length + "/" + b);
        for (var d = 0; d < a.length && 0 == a[d];) d++;
        this.num = Array(a.length - d + b);
        for (var c = 0; c < a.length - d; c++) this.num[c] = a[c + d]
    }

    QRPolynomial.prototype = {
        get: function (a) {
            return this.num[a]
        }, getLength: function () {
            return this.num.length
        }, multiply: function (a) {
            for (var b = Array(this.getLength() + a.getLength() - 1), d = 0; d < this.getLength(); d++) for (var c = 0; c < a.getLength(); c++) b[d + c] ^= QRMath.gexp(QRMath.glog(this.get(d)) + QRMath.glog(a.get(c)));
            return new QRPolynomial(b, 0)
        }, mod: function (a) {
            if (0 > this.getLength() - a.getLength()) return this;
            for (var b = QRMath.glog(this.get(0)) - QRMath.glog(a.get(0)), d = Array(this.getLength()), c = 0; c < this.getLength(); c++) d[c] =
                this.get(c);
            for (c = 0; c < a.getLength(); c++) d[c] ^= QRMath.gexp(QRMath.glog(a.get(c)) + b);
            return (new QRPolynomial(d, 0)).mod(a)
        }
    };

    function QRRSBlock(a, b) {
        this.totalCount = a;
        this.dataCount = b
    }

    QRRSBlock.RS_BLOCK_TABLE = [[1, 26, 19], [1, 26, 16], [1, 26, 13], [1, 26, 9], [1, 44, 34], [1, 44, 28], [1, 44, 22], [1, 44, 16], [1, 70, 55], [1, 70, 44], [2, 35, 17], [2, 35, 13], [1, 100, 80], [2, 50, 32], [2, 50, 24], [4, 25, 9], [1, 134, 108], [2, 67, 43], [2, 33, 15, 2, 34, 16], [2, 33, 11, 2, 34, 12], [2, 86, 68], [4, 43, 27], [4, 43, 19], [4, 43, 15], [2, 98, 78], [4, 49, 31], [2, 32, 14, 4, 33, 15], [4, 39, 13, 1, 40, 14], [2, 121, 97], [2, 60, 38, 2, 61, 39], [4, 40, 18, 2, 41, 19], [4, 40, 14, 2, 41, 15], [2, 146, 116], [3, 58, 36, 2, 59, 37], [4, 36, 16, 4, 37, 17], [4, 36, 12, 4, 37, 13], [2, 86, 68, 2, 87, 69], [4, 69, 43, 1, 70,
        44], [6, 43, 19, 2, 44, 20], [6, 43, 15, 2, 44, 16], [4, 101, 81], [1, 80, 50, 4, 81, 51], [4, 50, 22, 4, 51, 23], [3, 36, 12, 8, 37, 13], [2, 116, 92, 2, 117, 93], [6, 58, 36, 2, 59, 37], [4, 46, 20, 6, 47, 21], [7, 42, 14, 4, 43, 15], [4, 133, 107], [8, 59, 37, 1, 60, 38], [8, 44, 20, 4, 45, 21], [12, 33, 11, 4, 34, 12], [3, 145, 115, 1, 146, 116], [4, 64, 40, 5, 65, 41], [11, 36, 16, 5, 37, 17], [11, 36, 12, 5, 37, 13], [5, 109, 87, 1, 110, 88], [5, 65, 41, 5, 66, 42], [5, 54, 24, 7, 55, 25], [11, 36, 12], [5, 122, 98, 1, 123, 99], [7, 73, 45, 3, 74, 46], [15, 43, 19, 2, 44, 20], [3, 45, 15, 13, 46, 16], [1, 135, 107, 5, 136, 108], [10, 74, 46, 1,
        75, 47], [1, 50, 22, 15, 51, 23], [2, 42, 14, 17, 43, 15], [5, 150, 120, 1, 151, 121], [9, 69, 43, 4, 70, 44], [17, 50, 22, 1, 51, 23], [2, 42, 14, 19, 43, 15], [3, 141, 113, 4, 142, 114], [3, 70, 44, 11, 71, 45], [17, 47, 21, 4, 48, 22], [9, 39, 13, 16, 40, 14], [3, 135, 107, 5, 136, 108], [3, 67, 41, 13, 68, 42], [15, 54, 24, 5, 55, 25], [15, 43, 15, 10, 44, 16], [4, 144, 116, 4, 145, 117], [17, 68, 42], [17, 50, 22, 6, 51, 23], [19, 46, 16, 6, 47, 17], [2, 139, 111, 7, 140, 112], [17, 74, 46], [7, 54, 24, 16, 55, 25], [34, 37, 13], [4, 151, 121, 5, 152, 122], [4, 75, 47, 14, 76, 48], [11, 54, 24, 14, 55, 25], [16, 45, 15, 14, 46, 16], [6, 147,
        117, 4, 148, 118], [6, 73, 45, 14, 74, 46], [11, 54, 24, 16, 55, 25], [30, 46, 16, 2, 47, 17], [8, 132, 106, 4, 133, 107], [8, 75, 47, 13, 76, 48], [7, 54, 24, 22, 55, 25], [22, 45, 15, 13, 46, 16], [10, 142, 114, 2, 143, 115], [19, 74, 46, 4, 75, 47], [28, 50, 22, 6, 51, 23], [33, 46, 16, 4, 47, 17], [8, 152, 122, 4, 153, 123], [22, 73, 45, 3, 74, 46], [8, 53, 23, 26, 54, 24], [12, 45, 15, 28, 46, 16], [3, 147, 117, 10, 148, 118], [3, 73, 45, 23, 74, 46], [4, 54, 24, 31, 55, 25], [11, 45, 15, 31, 46, 16], [7, 146, 116, 7, 147, 117], [21, 73, 45, 7, 74, 46], [1, 53, 23, 37, 54, 24], [19, 45, 15, 26, 46, 16], [5, 145, 115, 10, 146, 116], [19,
        75, 47, 10, 76, 48], [15, 54, 24, 25, 55, 25], [23, 45, 15, 25, 46, 16], [13, 145, 115, 3, 146, 116], [2, 74, 46, 29, 75, 47], [42, 54, 24, 1, 55, 25], [23, 45, 15, 28, 46, 16], [17, 145, 115], [10, 74, 46, 23, 75, 47], [10, 54, 24, 35, 55, 25], [19, 45, 15, 35, 46, 16], [17, 145, 115, 1, 146, 116], [14, 74, 46, 21, 75, 47], [29, 54, 24, 19, 55, 25], [11, 45, 15, 46, 46, 16], [13, 145, 115, 6, 146, 116], [14, 74, 46, 23, 75, 47], [44, 54, 24, 7, 55, 25], [59, 46, 16, 1, 47, 17], [12, 151, 121, 7, 152, 122], [12, 75, 47, 26, 76, 48], [39, 54, 24, 14, 55, 25], [22, 45, 15, 41, 46, 16], [6, 151, 121, 14, 152, 122], [6, 75, 47, 34, 76, 48], [46,
        54, 24, 10, 55, 25], [2, 45, 15, 64, 46, 16], [17, 152, 122, 4, 153, 123], [29, 74, 46, 14, 75, 47], [49, 54, 24, 10, 55, 25], [24, 45, 15, 46, 46, 16], [4, 152, 122, 18, 153, 123], [13, 74, 46, 32, 75, 47], [48, 54, 24, 14, 55, 25], [42, 45, 15, 32, 46, 16], [20, 147, 117, 4, 148, 118], [40, 75, 47, 7, 76, 48], [43, 54, 24, 22, 55, 25], [10, 45, 15, 67, 46, 16], [19, 148, 118, 6, 149, 119], [18, 75, 47, 31, 76, 48], [34, 54, 24, 34, 55, 25], [20, 45, 15, 61, 46, 16]];
    QRRSBlock.getRSBlocks = function (a, b) {
        var d = QRRSBlock.getRsBlockTable(a, b);
        if (void 0 == d) throw Error("bad rs block @ typeNumber:" + a + "/errorCorrectLevel:" + b);
        for (var c = d.length / 3, e = [], f = 0; f < c; f++) for (var l = d[3 * f + 0], g = d[3 * f + 1], k = d[3 * f + 2], m = 0; m < l; m++) e.push(new QRRSBlock(g, k));
        return e
    };
    QRRSBlock.getRsBlockTable = function (a, b) {
        switch (b) {
            case QRErrorCorrectLevel.L:
                return QRRSBlock.RS_BLOCK_TABLE[4 * (a - 1) + 0];
            case QRErrorCorrectLevel.M:
                return QRRSBlock.RS_BLOCK_TABLE[4 * (a - 1) + 1];
            case QRErrorCorrectLevel.Q:
                return QRRSBlock.RS_BLOCK_TABLE[4 * (a - 1) + 2];
            case QRErrorCorrectLevel.H:
                return QRRSBlock.RS_BLOCK_TABLE[4 * (a - 1) + 3]
        }
    };

    function QRBitBuffer() {
        this.buffer = [];
        this.length = 0
    }

    QRBitBuffer.prototype = {
        get: function (a) {
            return 1 == (this.buffer[Math.floor(a / 8)] >>> 7 - a % 8 & 1)
        }, put: function (a, b) {
            for (var d = 0; d < b; d++) this.putBit(1 == (a >>> b - d - 1 & 1))
        }, getLengthInBits: function () {
            return this.length
        }, putBit: function (a) {
            var b = Math.floor(this.length / 8);
            this.buffer.length <= b && this.buffer.push(0);
            a && (this.buffer[b] |= 128 >>> this.length % 8);
            this.length++
        }
    };
</script>
<script>
    qrcode(document.getElementById('j-qrcode-con'));
</script>
                                <p class="fusion__qcode-txt">用最新版本的手机QQ扫码来玩</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <iframe src="https://mobile.qzone.qq.com/mapp/mapp_addAuthorize.cgi?&platform=wanba&appid=1106690716&ext_args=platform%3D2%26pf%3Dwanba_ts.98&_bid=201614&via=QZSTORE.V6.MY.APPS&resource=pc" frameborder="0" width="100%" height="100%" style="position: fixed;top:28px;bottom:0px;left:0px;" id="app_canvas_frame"></iframe>
        </div>
    </body>
    <script>
        window._reporterTime.jsReady = new Date().getTime();
    </script><script>
    (function() {
        var collector = [],
                collectorTime = 2000,
                collectorTimer;
        window.reportHaboGlobal = function (code, appid, command) {
            var ua = navigator.userAgent || '';
            var qzoneArray = /Qzone\/(\S+)/.exec(ua);
            var qqArray = /V\S+_\S+_\S+_\S+_\S+_\S+_\S+/.exec(ua);
            var apnArray = /NetType\/(\S+)/.exec(ua);
            var uinArray = /uin=o0*(\S+);/.exec(document.cookie || '');

            var qua = qzoneArray && qzoneArray[1] || qqArray && qqArray[0];
            var apn = apnArray && apnArray[1];
            var uin = uinArray && uinArray[1];
            command = (command || '');

            var data = {
                releaseversion: qua,
                apn: apn,
                touin: uin,
                key: 'appid,commandid,resultcode'
            };
            collector.push([appid || '1000361', 'hybrid/' + command, code]);

            var url = location.protocol === 'https:' ? 'https://h5.qzone.qq.com/wspeed.qq.com/w.cgi' : 'http://wspeed.qq.com/w.cgi';
            collectorTimer && clearTimeout(collectorTimer);
            collectorTimer = setTimeout(report, collectorTime);

            function report() {
                var params = [];
                for (var key in data) {
                    if (data.hasOwnProperty(key)) {
                        params.push(key + '=' + encodeURIComponent(data[key]));
                    }
                }
                if (collector && collector.length) {
                    var i = 0;
                    while (collector.length) {
                        if (params.join('&').length > 1000) {
                            break;
                        }
                        var c = collector.shift();
                        params.push([i + 1, 1].join('_') + '=' + c[0]);
                        params.push([i + 1, 2].join('_') + '=' + c[1]);
                        params.push([i + 1, 3].join('_') + '=' + c[2]);
                        i++;
                    }
                }
                params.push('rv=' + Math.random());
                params = params.join('&');
                url = url + '?' + params;
                new Image().src = url;

                if (i > 0) {
                    collector.length && setTimeout(report, 1000);//队列太长未上报完的1秒后再上报
                }
            }
        };
    })();
    (function() {
        var reportNum = 0;
        var beforeLoad = 1;
        var currentPath = getCurrentPath();
        /*
        * 当前路径，是上报成功率的命令字和jserror的path
        * 例如新版首页： /game/qzone
        * 其他页面，就是当前的path
        * 注意：由于错误上报到node，只允许上报两个path路径，所以当前业务的path大于3的时候，特殊处理下
        * 例如在哈勃和日报上查询首页：hybrid/game/qzone
        * */
        function getCurrentPath(){
            if(typeof window.reportPathname === 'string'){
                if(window.reportPathname.charAt(0) === '/'){
                    window.reportPathname = window.reportPathname.substring(1);
                }
                return window.reportPathname;
            }
            var pathname = location.pathname,
                tmp = pathname.split('/'),
                pathArray = [];

            for(var i=0,str;i<tmp.length;++i){
                str = tmp[i];
                if(str && str.length > 0){
                    pathArray.push(str);
                }
            }

            if(pathArray.length === 0){
                pathArray.push('game');
            }
            if(pathArray.length === 1){
                pathArray.push('index');
            }
            if(pathArray.length > 2){
                pathArray = [
                    'game',
                    pathArray.join('')
                ];
            }

            return pathArray.join('/')
        };
        function handleError(){
            var eventHandle = '',
                    event = {},// 事件对象
                    errorObj = {},
                    errMsg = '',
                    currenPath = currentPath,
                    errorUrl = '//h5.qzone.qq.com/log/post/error/' + currenPath;
            if(reportNum!=0){return;}
            reportNum = 1;
            if(typeof arguments.length > 1){
                eventHandle = 'DOM-ONE';
            }else if(arguments[0] !== 'trigger'){
                eventHandle = 'DOM-TWO';
            }else{
                eventHandle = 'trigger';
            }

            if(eventHandle === 'DOM-ONE'){
                event.message = arguments[0];
                event.filename = arguments[1];
                event.lineno = arguments[2];
                event.colno = arguments[3];
                errorObj = arguments[4];
                if(errorObj){
                    event.stack = errorObj.stack || '';
                }
            }else if(eventHandle === 'DOM-TWO'){
                event = arguments[0];
                errorObj = event.error || {};
                event.stack = errorObj.stack || '';
            }else if(eventHandle === 'trigger'){
                event = arguments[1];
            }

            errMsg = event.message;
            errMsg += ";url:" + location.href + ";";
            errMsg += "scriptURI:" + event.filename + ";";
            errMsg += "lineNumber:" + event.lineno + ";";
            errMsg += "columnNumber:" + event.colno + ";";
            errMsg += "beforeLoad:" + beforeLoad + ";";
            errMsg = errMsg.replace(/=|&/g,"");
            if(external && external.OnAppStoreWebLog){
                external.OnAppStoreWebLog('前端上报页面错误：'+'页面路径'+currenPath+'错误信息：'+errMsg);
            }
            if(top.Vconsole && top.Vconsole.log){
                top.Vconsole.log(errMsg);
            }
            var xhr;
            if (window.XMLHttpRequest){
                xhr=new XMLHttpRequest();
            } else{// code for IE8
                xhr=new ActiveXObject("Microsoft.XMLHTTP");
            }

            xhr.withCredentials = true;
            xhr.open('post', errorUrl, true);
            xhr.setRequestHeader('Content-Type', 'application/x-www-form-urlencoded');
            xhr.send(errMsg);
        };
        window.JSERROR = {};
        window.JSERROR._handleError = function (e){
            handleError('trigger',e);
        };
        function handleLoad(){
            beforeLoad = 0;
            !reportNum && window.reportHaboGlobal && reportHaboGlobal(reportNum,null,currentPath);
        }

        if(window.addEventListener){
            window.addEventListener('error', handleError);
            window.listenError = true;
            window.addEventListener('load',handleLoad);
        }else if(window.attachEvent){
            window.attachEvent('onerror',handleError);
            window.listenError = true;
            window.attachEvent('onload',handleLoad);
        }else{
            window.onerror = handleError;
            window.listenError = true;
            window.onload = handleLoad;
        }
    }());
</script>    <!--[if IE 8]>
    <script src="https://qzonestyle.gtimg.cn/qzone/appcenter/lib/babel-polyfill.js"></script>
    <![endif]--><script type="text/javascript">    window.enabledCrossOrigin = false;
</script>    <script>
    var SeajsloadErrorMap = {};
    (function(t,u){function v(b){return function(c){return Object.prototype.toString.call(c)==="[object "+b+"]"}}function Q(){return w++}function I(b,c){var a;a=b.charAt(0);if(R.test(b))a=b;else if("."===a){a=(c?c.match(E)[0]:h.cwd)+b;for(a=a.replace(S,"/");a.match(J);)a=a.replace(J,"/")}else a="/"===a?(a=h.cwd.match(T))?a[0]+b.substring(1):b:h.base+b;return a}function K(b,c){if(!b)return"";var a=b,d=h.alias,a=b=d&&F(d[a])?d[a]:a,d=h.paths,g;if(d&&(g=a.match(U))&&F(d[g[1]]))a=d[g[1]]+g[2];g=a;var e=h.vars;
        e&&-1<g.indexOf("{")&&(g=g.replace(V,function(a,b){return F(e[b])?e[b]:a}));a=g.length-1;d=g.charAt(a);b="#"===d?g.substring(0,a):".js"===g.substring(a-2)||0<g.indexOf("?")||".css"===g.substring(a-3)||"/"===d?g:g+".js";g=I(b,c);var a=h.map,l=g;if(a)for(var d=0,f=a.length;d<f&&!(l=a[d],l=x(l)?l(g)||g:g.replace(l[0],l[1]),l!==g);d++);return l}function L(b,c){var a=b.sheet,d;if(M)a&&(d=!0);else if(a)try{a.cssRules&&(d=!0)}catch(g){"NS_ERROR_DOM_SECURITY_ERR"===g.name&&(d=!0)}setTimeout(function(){d?
        c():L(b,c)},20)}function W(){if(y)return y;if(z&&"interactive"===z.readyState)return z;for(var b=s.getElementsByTagName("script"),c=b.length-1;0<=c;c--){var a=b[c];if("interactive"===a.readyState)return z=a}}function e(b,c){this.uri=b;this.dependencies=c||[];this.exports=null;this.status=0;this._waitings={};this._remain=0}if(!t.seajs){var f=t.seajs={version:"2.1.1"},h=f.data={},X=v("Object"),F=v("String"),A=Array.isArray||v("Array"),x=v("Function"),w=0,p=h.events={};f.on=function(b,c){(p[b]||(p[b]=
        [])).push(c);return f};f.off=function(b,c){if(!b&&!c)return p=h.events={},f;var a=p[b];if(a)if(c)for(var d=a.length-1;0<=d;d--)a[d]===c&&a.splice(d,1);else delete p[b];return f};var m=f.emit=function(b,c){var a=p[b],d;if(a)for(a=a.slice();d=a.shift();)d(c);return f},E=/[^?#]*\//,S=/\/\.\//g,J=/\/[^/]+\/\.\.\//,U=/^([^/:]+)(\/.+)$/,V=/{([^{]+)}/g,R=/^\/\/.|:\//,T=/^.*?\/\/.*?\//,n=document,q=location,B=q.href.match(E)[0],k=n.getElementsByTagName("script"),k=n.getElementById("seajsnode")||k[k.length-
        1],k=((k.hasAttribute?k.src:k.getAttribute("src",4))||B).match(E)[0],s=n.getElementsByTagName("head")[0]||n.documentElement,N=s.getElementsByTagName("base")[0],O=/\.css(?:\?|$)/i,Y=/^(?:loaded|complete|undefined)$/,y,z,M=536>1*navigator.userAgent.replace(/.*AppleWebKit\/(\d+)\..*/,"$1"),Z=/"(?:\\"|[^"])*"|'(?:\\'|[^'])*'|\/\*[\S\s]*?\*\/|\/(?:\\\/|[^\/\r\n])+\/(?=[^\/])|\/\/.*|\.\s*require|(?:^|[^$])\brequire\s*\(\s*(["'])(.+?)\1\s*\)/g,$=/\\\\/g,r=f.cache={},C,G={},H={},D={},j=e.STATUS={FETCHING:1,
        SAVED:2,LOADING:3,LOADED:4,EXECUTING:5,EXECUTED:6};e.prototype.resolve=function(){for(var b=this.dependencies,c=[],a=0,d=b.length;a<d;a++)c[a]=e.resolve(b[a],this.uri);return c};e.prototype.load=function(){if(!(this.status>=j.LOADING)){this.status=j.LOADING;var b=this.resolve();m("load",b);for(var c=this._remain=b.length,a,d=0;d<c;d++)a=e.get(b[d]),a.status<j.LOADED?a._waitings[this.uri]=(a._waitings[this.uri]||0)+1:this._remain--;if(0===this._remain)this.onload();else{for(var g={},d=0;d<c;d++)a=
        r[b[d]],a.status<j.FETCHING?a.fetch(g):a.status===j.SAVED&&a.load();for(var h in g)if(g.hasOwnProperty(h))g[h]()}}};e.prototype.onload=function(){this.status=j.LOADED;this.callback&&this.callback();var b=this._waitings,c,a;for(c in b)if(b.hasOwnProperty(c)&&(a=r[c],a._remain-=b[c],0===a._remain))a.onload();delete this._waitings;delete this._remain};e.prototype.fetch=function(b){function c(){var a=g.requestUri,b=g.onRequest,c=g.charset,d=O.test(a),e=n.createElement(d?"link":"script");if(c&&(c=x(c)?
            c(a):c))e.charset=c;var f=e;d&&(M||!("onload"in f))?setTimeout(function(){L(f,b)},1):f.onload=f.onreadystatechange=function(e){Y.test(f.readyState) && (f.onload=f.onerror=f.onreadystatechange=null,!d&&!h.debug&&s.removeChild(f),f=null,b(e))};f.onerror=function(e){SeajsloadErrorMap[f.src]=1;Y.test(f.readyState) && (f.onload=f.onerror=f.onreadystatechange=null,!d&&!h.debug&&s.removeChild(f),f=null,b(e))};d?(e.rel="stylesheet",e.href=a):(e.async=!0,e.src=a);y=e;N?s.insertBefore(e,N):s.appendChild(e);y=null}function a(){delete G[f];H[f]=!0;C&&(e.save(d,C),C=null);var a,b=D[f];for(delete D[f];a=b.shift();)a.load()}var d=this.uri;this.status=j.FETCHING;var g=
        {uri:d};m("fetch",g);var f=g.requestUri||d;!f||H[f]?this.load():G[f]?D[f].push(this):(G[f]=!0,D[f]=[this],m("request",g={uri:d,requestUri:f,onRequest:a,charset:h.charset}),g.requested||(b?b[g.requestUri]=c:c()))};e.prototype.exec=function(){function b(a){return e.get(b.resolve(a)).exec()}if(this.status>=j.EXECUTING)return this.exports;this.status=j.EXECUTING;var c=this.uri;b.resolve=function(a){return e.resolve(a,c)};b.async=function(a,g){e.use(a,g,c+"_async_"+w++);return b};var a=this.factory,a=
        x(a)?a(b,this.exports={},this):a;a===u&&(a=this.exports);null===a&&!O.test(c)&&m("error",this);delete this.factory;this.exports=a;this.status=j.EXECUTED;m("exec",this);return a};e.resolve=function(b,c){var a={id:b,refUri:c};m("resolve",a);return a.uri||K(a.id,c)};e.define=function(b,c,a){var d=arguments.length;1===d?(a=b,b=u):2===d&&(a=c,A(b)?(c=b,b=u):c=u);if(!A(c)&&x(a)){var g=[];a.toString().replace($,"").replace(Z,function(a,b,c){c&&g.push(c)});c=g}d={id:b,uri:e.resolve(b),deps:c,factory:a};if(!d.uri&&
        n.attachEvent){var f=W();f&&(d.uri=f.src)}m("define",d);d.uri?e.save(d.uri,d):C=d};e.save=function(b,c){var a=e.get(b);a.status<j.SAVED&&(a.id=c.id||b,a.dependencies=c.deps||[],a.factory=c.factory,a.status=j.SAVED)};e.get=function(b,c){return r[b]||(r[b]=new e(b,c))};e.use=function(b,c,a){var d=e.get(a,A(b)?b:[b]);d.callback=function(){for(var a=[],b=d.resolve(),e=0,f=b.length;e<f;e++)a[e]=r[b[e]].exec();c&&c.apply(t,a);delete d.callback};d.load()};e.preload=function(b){var c=h.preload,a=c.length;
        a?e.use(c,function(){c.splice(0,a);e.preload(b)},h.cwd+"_preload_"+w++):b()};f.use=function(b,c){e.preload(function(){e.use(b,c,h.cwd+"_use_"+w++)});return f};e.define.cmd={};t.define=e.define;f.Module=e;h.fetchedList=H;h.cid=Q;f.resolve=K;f.require=function(b){return(r[e.resolve(b)]||{}).exports};h.base=(k.match(/^(.+?\/)(\?\?)?(seajs\/)+/)||["",k])[1];h.dir=k;h.cwd=B;h.charset="utf-8";var B=h,P=[],q=q.search.replace(/(seajs-\w+)(&|$)/g,"$1=1$2"),q=q+(" "+n.cookie);q.replace(/(seajs-\w+)=1/g,function(b,c){P.push(c)});
        B.preload=P;f.config=function(b){for(var c in b){var a=b[c],d=h[c];if(d&&X(d))for(var e in a)d[e]=a[e];else A(d)?a=d.concat(a):"base"===c&&("/"===a.slice(-1)||(a+="/"),a=I(a)),h[c]=a}m("config",b);return f}}})(this);
    (function(){var retryMap={};seajs.on("request",function(data){var uri=data.uri;var mod=seajs.cache[uri];if(mod){var cb=data.onRequest||function(){};data.onRequest=function(e){var ars=arguments;if(!e){return cb.apply(window,ars)}if(e.type==="error"){if(retryMap[uri]){cb.apply(window,ars)}else{var retryUri=seajs.resolve(fixPath(uri));retryMap[uri]=retryUri;retryMap[retryUri]=true;seajs.use(retryUri,function(){if(seajs.cache[retryUri]){seajs.cache[uri].dependencies=seajs.cache[retryUri].dependencies;seajs.cache[uri].exports=seajs.cache[retryUri].exports}cb.apply(window,ars)})}}else{cb.apply(window,ars)}}}});function fixPath(path){if(path.indexOf("proxy/domain")===-1){path=path.replace("//","//h5.qzone.qq.com/proxy/domain/")}else{path=path.replace("h5.qzone.qq.com/proxy/domain/","")}return path}}());
</script>            <script src="https://qzonestyle.gtimg.cn/qzone/appcenter/lib/loader.js?version=20190312&max_age=2592000"></script>        <script src="https://qzonestyle.gtimg.cn/ac/qzfl/release/qzfl_for_qzone.js"></script>
    <script src="https://qzonestyle.gtimg.cn/c/=/qzone/v8/engine/migrate-plugin.js,/qzone/v8/engine/console-plus/console-plus.js,/qzone/v8/engine/request/request_60526.js,/qzone/v8/core/interface_mini.js?max_age=60628"></script>
    <script type="text/javascript" src="//qzonestyle.gtimg.cn/qzone/app/qzshare/script/qzshare.onekey.co.js" ></script>
    
    <script>
        window.h5 = true;
    
        window.g_R_Domain = 'gameapp.qq.com/proxy/domain/r.qzone.qq.com';
        window.g_domain = 'qq.com';
    
        
        QZONE = QZONE || {};
        QZONE.appCanvas = QZONE.appCanvas || {};
        QZONE.appCanvas.base = QZONE.appCanvas.base || {};
        QZONE.appCanvas.base.appInfo = {"appid":1106690716,"desc":"","alias":"猎鱼达人","gameSize":{"width":1120,"height":630},"canvasUrl":"https://mobile.qzone.qq.com/mapp/mapp_addAuthorize.cgi?&platform=wanba&appid=1106690716&ext_args=platform%3D2%26pf%3Dwanba_ts.98&_bid=201614&via=QZSTORE.V6.MY.APPS&resource=pc","appIcon":"http://i.gtimg.cn/open/app_icon/06/69/07/16/1106690716_100_m.png","display":1};
        QZONE.appCanvas.base.appid = 1106690716;
        QZONE.appCanvas.base.canvas_url = "https://mobile.qzone.qq.com/mapp/mapp_addAuthorize.cgi?&platform=wanba&appid=1106690716&ext_args=platform%3D2%26pf%3Dwanba_ts.98&_bid=201614&via=QZSTORE.V6.MY.APPS&resource=pc";
        QZONE.appCanvas.lang = {
            isQZONE: true
        };
        QZONE.appCanvas.isNeedLogin = true;
        var PARAM = {"gameInfo":{"appid":1106690716,"desc":"","alias":"猎鱼达人","gameSize":{"width":1120,"height":630},"canvasUrl":"https://mobile.qzone.qq.com/mapp/mapp_addAuthorize.cgi?&platform=wanba&appid=1106690716&ext_args=platform%3D2%26pf%3Dwanba_ts.98&_bid=201614&via=QZSTORE.V6.MY.APPS&resource=pc","appIcon":"http://i.gtimg.cn/open/app_icon/06/69/07/16/1106690716_100_m.png","display":1}};
        window.g_qzonetoken = '';
    </script>
    <script src="https://pingjs.qq.com/tcss.ping.js"></script>
    <script>
        seajs.use([window._CDN+'/qzone/appcenter/canvas/index.js?version=e788bb82&max_age=2592000', 'interface'], function (mod) {
            mod.init();
            setTimeout(function(){
                window._reporterTime.active = new Date().getTime();
            },0);
        });
        window._reporterTime.jsReady = new Date().getTime();
    </script>
    </body>
    </html>
