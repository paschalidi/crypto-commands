<div class="wrapper">
    <article class="post" itemscope="" itemtype="http://schema.org/BlogPosting">

        <header class="post-header">
            <h1 class="post-title" itemprop="name headline">PKCS #1, PKCS #8, X.509</h1>
            <p class="post-meta">
                <time datetime="2017-04-17T15:49:12-04:00" itemprop="datePublished">

                    Apr 17, 2017
                </time>

                • <span>Categories: Cryptography</span> • <span>Tags: cryptography, shell</span>
            </p>
        </header>

        <div class="post-content" itemprop="articleBody">
            <h2 id="rfc8017-pkcs-1-v22"><a href="https://tools.ietf.org/html/rfc8017#appendix-A.1">RFC8017</a> (PKCS #1 v.2.2)</h2>

            <p>Defines the traditional format for RSA keys. Two <strong>structures</strong>:</p>

            <figure class="code-highlight-figure">
                <div class="code-highlight"><pre class="code-highlight-pre"><div data-line="1" class="code-highlight-row numbered"><div class="code-highlight-line">-----BEGIN RSA PRIVATE KEY-----
</div></div><div data-line="2" class="code-highlight-row numbered"><div class="code-highlight-line">RSAPrivateKey
</div></div><div data-line="3" class="code-highlight-row numbered"><div class="code-highlight-line">-----END RSA PRIVATE KEY-----</div></div></pre></div>
            </figure>

            <p>and</p>

            <figure class="code-highlight-figure">
                <div class="code-highlight"><pre class="code-highlight-pre"><div data-line="1" class="code-highlight-row numbered"><div class="code-highlight-line">-----BEGIN RSA PUBLIC KEY-----
</div></div><div data-line="2" class="code-highlight-row numbered"><div class="code-highlight-line">RSAPublicKey
</div></div><div data-line="3" class="code-highlight-row numbered"><div class="code-highlight-line">-----END RSA PUBLIC KEY-----</div></div></pre></div>
            </figure>

            <p><strong>Commands</strong></p>

            <p>Generate RSA private key</p>

            <div class="highlighter-rouge">
                <div class="highlight"><pre class="highlight"><code>openssl genrsa -out private.pem 2048
</code></pre></div>
            </div>

            <p>Extract public key from RSA private key</p>

            <div class="highlighter-rouge">
                <div class="highlight"><pre class="highlight"><code>openssl rsa -in private.pem -out public.pem -RSAPublicKey_out
</code></pre></div>
            </div>

            <!-- more -->

            <h2 id="rfc5958-former-pkcs-8-aka-p8"><a href="https://tools.ietf.org/html/rfc5958#section-5">RFC5958</a> (former PKCS #8, aka .p8)</h2>

            <p>Defines the format for any private key. Two <strong>structures</strong>:</p>

            <figure class="code-highlight-figure">
                <div class="code-highlight"><pre class="code-highlight-pre"><div data-line="1" class="code-highlight-row numbered"><div class="code-highlight-line">-----BEGIN PRIVATE KEY-----
</div></div><div data-line="2" class="code-highlight-row numbered"><div class="code-highlight-line">PrivateKeyInfo ::= OneAsymmetricKey
</div></div><div data-line="3" class="code-highlight-row numbered"><div class="code-highlight-line">-----END PRIVATE KEY-----</div></div></pre></div>
            </figure>

            <p>and</p>

            <figure class="code-highlight-figure">
                <div class="code-highlight"><pre class="code-highlight-pre"><div data-line="1" class="code-highlight-row numbered"><div class="code-highlight-line">-----BEGIN ENCRYPTED PRIVATE KEY-----
</div></div><div data-line="2" class="code-highlight-row numbered"><div class="code-highlight-line">EncryptedPrivateKeyInfo
</div></div><div data-line="3" class="code-highlight-row numbered"><div class="code-highlight-line">-----END ENCRYPTED PRIVATE KEY-----</div></div></pre></div>
            </figure>

            <p>The corresponding PEM formats are described in RFC7468 <a href="https://tools.ietf.org/html/rfc7468#section-10">Section 10</a> and <a href="https://tools.ietf.org/html/rfc7468#section-11">Section 11</a>.</p>

            <p><strong>Commands</strong></p>

            <p class=" has-jax">Convert PKCS #1 <span class="MathJax_Preview" style="color: inherit; display: none;"></span><span id="MathJax-Element-1-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mo stretchy=&quot;false&quot;>&amp;#x2192;</mo></math>" role="presentation" style="font-size: 116%; position: relative;"><span id="MJXc-Node-1" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-2" class="mjx-mrow"><span id="MJXc-Node-3" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.218em; padding-bottom: 0.326em;">→</span></span>
                </span>
                </span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo stretchy="false">→</mo></math></span></span>
                <script type="math/tex" id="MathJax-Element-1">\rightarrow</script> PKCS #8</p>

            <div class="highlighter-rouge">
                <div class="highlight"><pre class="highlight"><code>openssl pkcs8 -in private-pkcs1.pem -topk8 -out private-pkcs8.pem -nocrypt
openssl pkcs8 -in private-pkcs1.pem -topk8 -out private-pkcs8-enc.pem
</code></pre></div>
            </div>

            <p class=" has-jax">Convert PKCS #8 <span class="MathJax_Preview" style="color: inherit; display: none;"></span><span id="MathJax-Element-2-Frame" class="mjx-chtml MathJax_CHTML" tabindex="0" data-mathml="<math xmlns=&quot;http://www.w3.org/1998/Math/MathML&quot;><mo stretchy=&quot;false&quot;>&amp;#x2192;</mo></math>" role="presentation" style="font-size: 116%; position: relative;"><span id="MJXc-Node-4" class="mjx-math" aria-hidden="true"><span id="MJXc-Node-5" class="mjx-mrow"><span id="MJXc-Node-6" class="mjx-mo"><span class="mjx-char MJXc-TeX-main-R" style="padding-top: 0.218em; padding-bottom: 0.326em;">→</span></span>
                </span>
                </span><span class="MJX_Assistive_MathML" role="presentation"><math xmlns="http://www.w3.org/1998/Math/MathML"><mo stretchy="false">→</mo></math></span></span>
                <script type="math/tex" id="MathJax-Element-2">\rightarrow</script> PKCS #1</p>

            <div class="highlighter-rouge">
                <div class="highlight"><pre class="highlight"><code>openssl rsa -in private-pkcs8.pem -out private-pkcs1.pem
</code></pre></div>
            </div>

            <h2 id="rfc5280-pki-x509"><a href="https://tools.ietf.org/html/rfc5280#section-4.1.2.7">RFC5280</a> (PKI X.509)</h2>

            <p>Among other things, defines the format for any public key</p>

            <figure class="code-highlight-figure">
                <div class="code-highlight"><pre class="code-highlight-pre"><div data-line="1" class="code-highlight-row numbered"><div class="code-highlight-line">-----BEGIN PUBLIC KEY-----
</div></div><div data-line="2" class="code-highlight-row numbered"><div class="code-highlight-line">SubjectPublicKeyInfo
</div></div><div data-line="3" class="code-highlight-row numbered"><div class="code-highlight-line">-----END PUBLIC KEY-----</div></div></pre></div>
            </figure>

            <p>The PEM format is described in <a href="https://tools.ietf.org/html/rfc7468#section-13">RFC7468</a>.</p>

            <p><strong>Commands</strong></p>

            <p>Convert RSA public key between X.509 and PKCS #1 formats</p>

            <div class="highlighter-rouge">
                <div class="highlight"><pre class="highlight"><code>openssl rsa -pubin -in public.pem -RSAPublicKey_out
openssl rsa -RSAPublicKey_in -in pkcs1-public.pem -pubout
</code></pre></div>
            </div>

            <p>Extract public key from RSA private key</p>

            <div class="highlighter-rouge">
                <div class="highlight"><pre class="highlight"><code>openssl rsa -in private.pem -out public.pem -pubout
</code></pre></div>
            </div>

            <p>Extract public key from X.509 CSR</p>

            <div class="highlighter-rouge">
                <div class="highlight"><pre class="highlight"><code>openssl req -in cert.csr -pubkey -noout
</code></pre></div>
            </div>

            <p>Extract public key from X.509 certificate</p>

            <div class="highlighter-rouge">
                <div class="highlight"><pre class="highlight"><code>openssl x509 -in cert.crt -inform pem -pubkey -noout
openssl x509 -in cert.cer -inform der -pubkey -noout
</code></pre></div>
            </div>

            <p>Convert X.509 certificate between DER and PEM formats</p>

            <div class="highlighter-rouge">
                <div class="highlight"><pre class="highlight"><code>openssl x509 -in cert.cer -inform der -out cert.crt -outform pem
openssl x509 -in cert.crt -inform pem -out cert.cer -outform der
</code></pre></div>
            </div>

        </div>

    </article>

</div>
