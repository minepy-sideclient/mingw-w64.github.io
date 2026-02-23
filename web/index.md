<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">
<head>
  <meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
  <meta name="description" content="Mingw-w64 - GCC for Windows 64 & 32 bits" />
  <title>Mingw-w64 - GCC for Windows 64 &amp; 32 bits</title>
  <style type="text/css">

    body {
      background-color: #d4d0c8;
      background-image: url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAQAAAAECAYAAACp8Z5+AAAAFklEQVQI12NggAEmQFzCgAkGBgYGAB4AAAQAAAHbSZIAAAAASUVORK5CYII=");
      font-family: Verdana, Arial, sans-serif;
      font-size: 12px;
      color: #000000;
      margin: 0;
      padding: 0;
    }

    a { color: #0000cc; }
    a:visited { color: #551a8b; }
    a:hover { color: #cc0000; text-decoration: underline; }

    #wrapper {
      width: 780px;
      margin: 10px auto;
    }

    /* BANNER */
    #banner {
      background: linear-gradient(to bottom, #3a6fc4 0%, #1e4a9e 40%, #163a82 100%);
      border: 2px solid;
      border-color: #ffffff #808080 #808080 #ffffff;
      padding: 0;
      margin-bottom: 4px;
      overflow: hidden;
    }

    #banner-inner {
      display: table;
      width: 100%;
    }

    #banner-left {
      display: table-cell;
      padding: 14px 20px;
      vertical-align: middle;
    }

    #banner h1 {
      font-family: "Times New Roman", Times, serif;
      font-size: 28px;
      font-weight: bold;
      color: #ffffff;
      text-shadow: 2px 2px 0px #00008b;
      margin: 0 0 2px 0;
      letter-spacing: 1px;
    }

    #banner h1 span { color: #ffdd44; }

    #banner-sub {
      font-size: 11px;
      color: #c8d8ff;
      font-style: italic;
    }

    #banner-right {
      display: table-cell;
      text-align: right;
      padding: 10px 14px;
      vertical-align: middle;
    }

    .badge {
      display: inline-block;
      background: #ff6600;
      color: #ffffff;
      font-size: 9px;
      font-weight: bold;
      font-family: Verdana, sans-serif;
      padding: 2px 6px;
      border: 1px solid #cc4400;
      text-transform: uppercase;
      letter-spacing: 1px;
      margin-left: 4px;
    }

    /* NAV */
    #navbar {
      background: linear-gradient(to bottom, #ece9d8, #d4d0c8);
      border: 1px solid;
      border-color: #ffffff #808080 #808080 #ffffff;
      padding: 3px 6px;
      margin-bottom: 4px;
    }

    #navbar a {
      font-size: 11px;
      color: #000000;
      text-decoration: none;
      padding: 2px 10px;
      border-right: 1px solid #808080;
      font-weight: bold;
    }

    #navbar a:last-child { border-right: none; }
    #navbar a:hover { color: #0000cc; text-decoration: underline; }

    /* TICKER */
    .ticker-wrap {
      background: #000080;
      color: #ffffff;
      font-size: 11px;
      font-family: "Courier New", monospace;
      padding: 3px 6px;
      overflow: hidden;
      white-space: nowrap;
      margin-bottom: 4px;
    }

    .ticker-inner {
      display: inline-block;
      animation: ticker 35s linear infinite;
    }

    @keyframes ticker {
      from { transform: translateX(800px); }
      to   { transform: translateX(-100%); }
    }

    /* LAYOUT */
    #main-table { width: 100%; border-collapse: collapse; }
    #sidebar { width: 170px; vertical-align: top; padding-right: 6px; }
    #content { vertical-align: top; padding-left: 4px; }

    /* SIDEBAR BOXES */
    .side-box {
      margin-bottom: 8px;
      border: 1px solid;
      border-color: #808080 #ffffff #ffffff #808080;
      background: #ece9d8;
    }

    .side-box-title {
      background: linear-gradient(to bottom, #3a6fc4, #1e4a9e);
      color: #ffffff;
      font-size: 11px;
      font-weight: bold;
      padding: 3px 6px;
    }

    .side-box-body { padding: 6px 8px; font-size: 11px; }

    .side-box-body a {
      display: block;
      padding: 2px 0;
      border-bottom: 1px dotted #c0bdb0;
      font-size: 11px;
    }

    .side-box-body a:last-child { border-bottom: none; }

    .side-counter {
      background: #ffffff;
      border: 1px inset #808080;
      text-align: center;
      padding: 6px;
      font-family: "Courier New", monospace;
      font-size: 18px;
      font-weight: bold;
      color: #003399;
      letter-spacing: 2px;
    }

    /* CONTENT BOXES */
    .content-box {
      margin-bottom: 10px;
      border: 2px solid;
      border-color: #ffffff #808080 #808080 #ffffff;
      background: #ffffff;
    }

    .content-box-title {
      background: linear-gradient(to bottom, #3a6fc4 0%, #1e4a9e 100%);
      color: #ffffff;
      font-size: 13px;
      font-weight: bold;
      padding: 4px 10px;
      border-bottom: 2px solid #1a3a7e;
    }

    .content-box-body { padding: 10px 12px; line-height: 1.6; }
    .content-box-body p { margin: 0 0 8px 0; }

    /* FEATURE TABLE */
    .feature-table { width: 100%; border-collapse: collapse; font-size: 11px; }
    .feature-table th {
      background: #d4d0c8;
      border: 1px solid #808080;
      padding: 4px 8px;
      text-align: left;
      font-weight: bold;
    }
    .feature-table td { border: 1px solid #c0bdb0; padding: 4px 8px; vertical-align: top; }
    .feature-table tr:nth-child(even) td { background: #f5f4ef; }
    .feature-table tr:hover td { background: #ddeeff; }

    /* TOOLS */
    .tool-row {
      border-bottom: 1px dotted #c0bdb0;
      padding: 6px 0;
      display: table;
      width: 100%;
    }
    .tool-row:last-child { border-bottom: none; }
    .tool-name-cell {
      display: table-cell;
      width: 80px;
      font-family: "Courier New", monospace;
      font-weight: bold;
      color: #003399;
      font-size: 12px;
      vertical-align: top;
      padding-top: 1px;
    }
    .tool-desc-cell { display: table-cell; font-size: 11px; color: #333; }

    /* PROJECT LIST */
    .proj-cols { column-count: 3; column-gap: 10px; font-size: 11px; }
    .proj-cols a {
      display: block;
      padding: 1px 0;
      white-space: nowrap;
      overflow: hidden;
      text-overflow: ellipsis;
      border-bottom: 1px dotted #ddd;
      break-inside: avoid;
    }

    /* COLLAB TABLE */
    .collab-table { width: 100%; border-collapse: collapse; text-align: center; font-size: 11px; }
    .collab-table td {
      padding: 10px;
      border: 1px solid #c0bdb0;
      vertical-align: middle;
      background: #f5f4ef;
    }
    .collab-table td:hover { background: #ddeeff; }
    .collab-name { font-weight: bold; font-size: 12px; display: block; margin-top: 4px; }

    /* NOTICE */
    .notice {
      background: #ffffc0;
      border: 1px solid #cccc00;
      padding: 6px 10px;
      font-size: 11px;
      margin-bottom: 10px;
    }

    /* BUTTON */
    .btn-win {
      display: inline-block;
      background: linear-gradient(to bottom, #ece9d8, #d4d0c8);
      border: 2px solid;
      border-color: #ffffff #808080 #808080 #ffffff;
      padding: 3px 12px;
      font-size: 11px;
      font-family: Verdana, sans-serif;
      text-decoration: none;
      color: #000000;
      cursor: pointer;
    }
    .btn-win:hover { background: linear-gradient(to bottom, #ddeeff, #b0c8e8); color: #000000; text-decoration: none; }

    /* FOOTER */
    #footer {
      background: #d4d0c8;
      border: 1px solid;
      border-color: #ffffff #808080 #808080 #ffffff;
      padding: 5px 10px;
      font-size: 10px;
      color: #444;
      text-align: center;
      margin-top: 6px;
    }

    .hl { color: #cc0000; font-weight: bold; }
    .mono { font-family: "Courier New", monospace; font-size: 11px; background: #f0f0f0; padding: 1px 3px; border: 1px solid #ccc; }

  </style>
</head>
<body>

<div id="wrapper">

  <!-- BANNER -->
  <div id="banner">
    <div id="banner-inner">
      <div id="banner-left">
        <h1>Mingw-<span>w64</span></h1>
        <div id="banner-sub">GCC for Windows 64 &amp; 32 bits &mdash; Free, Open Source, Since 2007</div>
      </div>
      <div id="banner-right">
        <span class="badge">v11.0</span>
        <span class="badge">Stable</span>
        <br /><br />
        <a href="https://www.mingw-w64.org" class="btn-win">&#8658; Download Now</a>
      </div>
    </div>
  </div>

  <!-- TICKER -->
  <div class="ticker-wrap">
    <span class="ticker-inner">
      &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
      *** NEW: mingw-w64 v11.0 released! *** &nbsp;&nbsp;|&nbsp;&nbsp;
      Supports GCC 13 and LLVM/Clang &nbsp;&nbsp;|&nbsp;&nbsp;
      Improved ARM64 headers now available &nbsp;&nbsp;|&nbsp;&nbsp;
      Used by Blender, FFmpeg, VLC, Qt, LibreOffice, and 70+ more projects &nbsp;&nbsp;|&nbsp;&nbsp;
      Forked from mingw.org in 2007 to bring 64-bit support &nbsp;&nbsp;|&nbsp;&nbsp;
      *** Free &amp; Open Source Software ***
    </span>
  </div>

  <!-- NAV -->
  <div id="navbar">
    <a href="#about">About</a>
    <a href="#features">Features</a>
    <a href="#tools">Tools</a>
    <a href="#collabs">Collaborations</a>
    <a href="#projects">Projects</a>
    <a href="https://github.com/mingw-w64/mingw-w64">Source Code</a>
    <a href="https://www.mingw-w64.org">Official Site</a>
  </div>

  <!-- MAIN LAYOUT -->
  <table id="main-table" cellspacing="0" cellpadding="0">
    <tr>

      <!-- SIDEBAR -->
      <td id="sidebar">

        <div class="side-box">
          <div class="side-box-title">&#9658; Quick Links</div>
          <div class="side-box-body">
            <a href="https://www.mingw-w64.org">Official Website</a>
            <a href="https://github.com/mingw-w64/mingw-w64">GitHub Repository</a>
            <a href="https://www.msys2.org">MSYS2 (recommended)</a>
            <a href="https://fedoraproject.org/wiki/MinGW">Fedora Cross-Compiler</a>
            <a href="https://sourceforge.net/projects/mingw-w64/">SourceForge Mirror</a>
          </div>
        </div>

        <div class="side-box">
          <div class="side-box-title">&#9658; Visitor Counter</div>
          <div class="side-box-body">
            <div class="side-counter">0148273</div>
            <div style="text-align:center; font-size:10px; margin-top:3px; color:#666;">visitors since 2007</div>
          </div>
        </div>

        <div class="side-box">
          <div class="side-box-title">&#9658; Compatibility</div>
          <div class="side-box-body">
            <div style="margin-bottom:3px;">&#10003; Windows XP+</div>
            <div style="margin-bottom:3px;">&#10003; Windows Vista</div>
            <div style="margin-bottom:3px;">&#10003; Windows 7</div>
            <div style="margin-bottom:3px;">&#10003; Windows 10/11</div>
            <div style="margin-bottom:3px;">&#10003; Linux (cross)</div>
            <div>&#10003; macOS (cross)</div>
          </div>
        </div>

        <div class="side-box">
          <div class="side-box-title">&#9658; Sister Projects</div>
          <div class="side-box-body">
            <a href="https://cygwin.com">Cygwin</a>
            <a href="https://reactos.org">ReactOS</a>
            <a href="https://winehq.org">Wine HQ</a>
            <a href="https://www.msys2.org">MSYS2</a>
          </div>
        </div>

        <div style="text-align:center; margin-top:8px;">
          <img src="https://www.gnu.org/graphics/gplv3-88x31.png" width="88" height="31" alt="GPLv3" style="border:1px solid #808080;" />
        </div>

      </td>

      <!-- CONTENT -->
      <td id="content">

        <div class="notice">
          &#9888; <strong>Note:</strong> This project is an advancement of the original
          <a href="http://www.mingw.org">mingw.org</a> project.
          It was forked in <strong>2007</strong> to provide 64-bit support and newer Windows APIs.
          <a href="https://www.mingw-w64.org">Download the latest release &raquo;</a>
        </div>

        <!-- ABOUT -->
        <a name="about"></a>
        <div class="content-box">
          <div class="content-box-title">About Mingw-w64</div>
          <div class="content-box-body">
            <p>
              <strong>Mingw-w64</strong> is a collection of header files, import libraries, libraries and tools that,
              combined with a compiler toolchain such as <strong>GCC</strong> or <strong>LLVM</strong>, provides
              a complete development environment for building native Windows applications and libraries.
            </p>
            <p>
              It was forked from <a href="http://www.mingw.org">mingw.org</a> in <span class="hl">2007</span>
              to provide proper 64-bit support and access to newer Windows APIs.
              Since then it has gained very wide use and distribution across many platforms.
            </p>
            <p>
              <a href="https://www.mingw-w64.org" class="btn-win">&#8658; Download Mingw-w64</a>
              &nbsp;
              <a href="https://github.com/mingw-w64/mingw-w64" class="btn-win">Browse Source Code</a>
            </p>
          </div>
        </div>

        <!-- FEATURES -->
        <a name="features"></a>
        <div class="content-box">
          <div class="content-box-title">Features &amp; Runtime Libraries</div>
          <div class="content-box-body">
            <table class="feature-table" cellspacing="0" cellpadding="0">
              <tr>
                <th width="160">Component</th>
                <th>Description</th>
              </tr>
              <tr>
                <td><strong>Headers &amp; Libraries</strong></td>
                <td>More than <span class="hl">1,000,000+ lines</span> of headers (not counting generated ones),
                regularly expanded to track new Windows APIs. Everything needed to link and run code on Windows.</td>
              </tr>
              <tr>
                <td><strong>Math Support</strong></td>
                <td>Better-conforming and faster math support compared to Visual Studio's runtime library. No compromises.</td>
              </tr>
              <tr>
                <td><span class="mono">winpthreads</span></td>
                <td>A pthreads library for C++11 threading support and simple integration with existing projects.</td>
              </tr>
              <tr>
                <td><span class="mono">winstorecompat</span></td>
                <td>Work-in-progress convenience library that eases conformance with the Windows Store.</td>
              </tr>
            </table>
          </div>
        </div>

        <!-- TOOLS -->
        <a name="tools"></a>
        <div class="content-box">
          <div class="content-box-title">Included Tools</div>
          <div class="content-box-body">
            <div class="tool-row">
              <div class="tool-name-cell">gendef</div>
              <div class="tool-desc-cell">Generate Visual Studio <span class="mono">.def</span> files from <span class="mono">.dll</span> files.</div>
            </div>
            <div class="tool-row">
              <div class="tool-name-cell">genidl</div>
              <div class="tool-desc-cell">Generate <span class="mono">.idl</span> interface definition files from <span class="mono">.dll</span> files.</div>
            </div>
            <div class="tool-row">
              <div class="tool-name-cell">widl</div>
              <div class="tool-desc-cell">Compile <span class="mono">.idl</span> files into headers and proxy stubs.</div>
            </div>
          </div>
        </div>

        <!-- COLLABORATIONS -->
        <a name="collabs"></a>
        <div class="content-box">
          <div class="content-box-title">Project Collaborations</div>
          <div class="content-box-body">
            <p style="margin-bottom:8px;">Mingw-w64 interacts with many projects. Contributions go to and come from:</p>
            <table class="collab-table" cellspacing="2" cellpadding="0">
              <tr>
                <td>
                  <span style="font-size:24px;">&#128187;</span>
                  <span class="collab-name"><a href="https://cygwin.com">Cygwin</a></span>
                </td>
                <td>
                  <span style="font-size:24px;">&#128187;</span>
                  <span class="collab-name"><a href="https://reactos.org">ReactOS</a></span>
                </td>
                <td>
                  <span style="font-size:24px;">&#127863;</span>
                  <span class="collab-name"><a href="https://winehq.org">Wine</a></span>
                </td>
                <td>
                  <span style="font-size:24px;">&#128187;</span>
                  <span class="collab-name"><a href="https://www.msys2.org">MSYS2</a></span>
                </td>
              </tr>
            </table>
          </div>
        </div>

        <!-- PROJECTS -->
        <a name="projects"></a>
        <div class="content-box">
          <div class="content-box-title">Projects Using Mingw-w64</div>
          <div class="content-box-body">
            <p style="margin-bottom:8px;"><em>These well-known open source projects build with mingw-w64.
            <a href="#">Feel free to add yours to this list!</a></em></p>
            <div class="proj-cols">
              <a href="https://gcc.gnu.org/">GCC</a>
              <a href="https://www.blender.org/">Blender</a>
              <a href="https://ffmpeg.mplayerhq.hu/">FFmpeg</a>
              <a href="https://www.gimp.org">GIMP</a>
              <a href="https://kde.org/">KDE Software Collection</a>
              <a href="https://www.libreoffice.org/">LibreOffice</a>
              <a href="https://www.videolan.org/vlc/">VideoLAN VLC</a>
              <a href="https://qt-project.org/">Qt</a>
              <a href="https://www.openssl.org/">OpenSSL</a>
              <a href="https://www.postgresql.org/">PostgreSQL</a>
              <a href="https://www.boost.org/">Boost</a>
              <a href="https://qemu.org">QEMU</a>
              <a href="https://mamedev.org/">MAME</a>
              <a href="https://www.r-project.org/">R Project</a>
              <a href="https://kotlinlang.org">Kotlin</a>
              <a href="https://www.perl.org/">Perl 5.12+</a>
              <a href="https://strawberryperl.com/">Strawberry Perl</a>
              <a href="https://libvirt.org/">libvirt</a>
              <a href="https://www.wxwidgets.org/">wxWidgets</a>
              <a href="https://www.gtk.org/">GTK+</a>
              <a href="https://strongswan.org/">strongSwan</a>
              <a href="https://www.gnu.org/software/gdb/">GDB</a>
              <a href="https://www.gnu.org/software/binutils/">GNU Binutils</a>
              <a href="https://www.imagemagick.org/">ImageMagick</a>
              <a href="https://www.fltk.org/">FLTK</a>
              <a href="https://www.mpg123.de/">mpg123</a>
              <a href="https://www.ocaml.org">OCaml</a>
              <a href="https://devkitpro.org/">devkitPro</a>
              <a href="https://www.zlib.net/">zlib</a>
              <a href="https://www.yafaray.org/">YafaRay</a>
              <a href="https://www.ecere.org/">Ecere SDK</a>
              <a href="https://factorcode.org/">Factor</a>
              <a href="https://www.webmproject.org/">libvpx</a>
              <a href="https://opensuse.org">OpenSUSE</a>
              <a href="https://www.gnu.org/software/gnutls/">GnuTLS</a>
            </div>
          </div>
        </div>

      </td>
    </tr>
  </table>

  <!-- FOOTER -->
  <div id="footer">
    &copy; 2007&ndash;2024 The Mingw-w64 Project &nbsp;|&nbsp;
    Licensed under MIT / ZPL / Public Domain &nbsp;|&nbsp;
    Hosted on <a href="https://sourceforge.net">SourceForge</a> &amp; <a href="https://github.com">GitHub</a>
    &nbsp;|&nbsp; Best viewed at 1024x768 &nbsp;|&nbsp;
    <a href="https://validator.w3.org/">Valid XHTML 1.0</a>
  </div>

</div>

<!-- i love mingw-64! -->

</body>
</html>
