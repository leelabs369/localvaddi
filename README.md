<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Privacy Policy - LocalVaddi</title>
    <style>
        :root {
            --primary-color: #1a56db;
            --primary-hover: #1e429f;
            --bg-color: #f8fafc;
            --card-bg: #ffffff;
            --text-main: #1e293b;
            --text-muted: #64748b;
            --border-color: #e2e8f0;
            --accent-bg: #eff6ff;
            --accent-border: #bfdbfe;
        }

        @media (prefers-color-scheme: dark) {
            :root {
                --primary-color: #3b82f6;
                --primary-hover: #60a5fa;
                --bg-color: #0f172a;
                --card-bg: #1e293b;
                --text-main: #f8fafc;
                --text-muted: #94a3b8;
                --border-color: #334155;
                --accent-bg: #1e3a8a33;
                --accent-border: #1e40af;
            }
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-main);
            line-height: 1.6;
            padding: 20px 16px;
        }

        .container {
            max-width: 860px;
            margin: 0 auto;
        }

        header {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 16px;
            padding: 32px 24px;
            margin-bottom: 24px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
            text-align: center;
        }

        .app-badge {
            display: inline-block;
            background-color: var(--accent-bg);
            color: var(--primary-color);
            border: 1px solid var(--accent-border);
            padding: 6px 14px;
            border-radius: 20px;
            font-size: 0.875rem;
            font-weight: 600;
            margin-bottom: 12px;
        }

        h1 {
            font-size: 2.25rem;
            font-weight: 800;
            margin-bottom: 8px;
            color: var(--text-main);
        }

        .subtitle {
            color: var(--text-muted);
            font-size: 0.95rem;
        }

        .content-card {
            background-color: var(--card-bg);
            border: 1px solid var(--border-color);
            border-radius: 16px;
            padding: 32px 28px;
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
        }

        nav.toc {
            background-color: var(--accent-bg);
            border: 1px solid var(--accent-border);
            border-radius: 12px;
            padding: 20px 24px;
            margin-bottom: 32px;
        }

        nav.toc h2 {
            font-size: 1.1rem;
            color: var(--primary-color);
            margin-bottom: 12px;
        }

        nav.toc ul {
            list-style: none;
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
            gap: 8px 16px;
        }

        nav.toc a {
            color: var(--text-main);
            text-decoration: none;
            font-size: 0.9rem;
            font-weight: 500;
            transition: color 0.2s ease;
        }

        nav.toc a:hover {
            color: var(--primary-color);
            text-decoration: underline;
        }

        section {
            margin-bottom: 36px;
        }

        section:last-child {
            margin-bottom: 0;
        }

        h2 {
            font-size: 1.4rem;
            font-weight: 700;
            margin-bottom: 14px;
            color: var(--primary-color);
            border-bottom: 2px solid var(--border-color);
            padding-bottom: 6px;
        }

        h3 {
            font-size: 1.1rem;
            font-weight: 600;
            margin: 16px 0 8px 0;
            color: var(--text-main);
        }

        p {
            margin-bottom: 12px;
            font-size: 0.975rem;
            color: var(--text-main);
        }

        ul, ol {
            margin-left: 20px;
            margin-bottom: 12px;
        }

        li {
            margin-bottom: 6px;
            font-size: 0.95rem;
        }

        .permission-box {
            background-color: var(--bg-color);
            border-left: 4px solid var(--primary-color);
            padding: 12px 16px;
            margin-bottom: 12px;
            border-radius: 0 8px 8px 0;
        }

        .permission-title {
            font-weight: 700;
            color: var(--text-main);
        }

        .contact-card {
            background-color: var(--accent-bg);
            border: 1px solid var(--accent-border);
            border-radius: 12px;
            padding: 20px;
            margin-top: 16px;
        }

        footer {
            text-align: center;
            margin-top: 32px;
            padding: 16px;
            font-size: 0.85rem;
            color: var(--text-muted);
        }

        footer a {
            color: var(--primary-color);
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }

        .link-placeholder {
            background-color: #fef08a;
            color: #854d0e;
            padding: 2px 6px;
            border-radius: 4px;
            font-family: monospace;
            font-size: 0.85rem;
        }
    </style>
</head>
<body>

<div class="container">
    <header>
        <span class="app-badge">LocalVaddi Application</span>
        <h1>Privacy Policy</h1>
        <p class="subtitle">Effective Date: July 26, 2026 | Last Updated: July 26, 2026</p>
    </header>

    <div class="content-card">
        <nav class="toc">
            <h2>Table of Contents</h2>
            <ul>
                <li><a href="#overview">1. Overview & Scope</a></li>
                <li><a href="#information-collected">2. Information We Collect</a></li>
                <li><a href="#how-we-use-data">3. How We Use Your Data</a></li>
                <li><a href="#permissions">4. App Permissions & Purpose</a></li>
                <li><a href="#storage-security">5. Data Storage & Security</a></li>
                <li><a href="#third-party-services">6. Third-Party Services</a></li>
                <li><a href="#data-sharing">7. Data Sharing & Disclosure</a></li>
                <li><a href="#user-rights">8. Your Rights & Data Erasure</a></li>
                <li><a href="#biometrics">9. Biometrics & Lock Features</a></li>
                <li><a href="#childrens-privacy">10. Children's Privacy</a></li>
                <li><a href="#policy-changes">11. Changes to This Policy</a></li>
                <li><a href="#contact-us">12. Contact Information</a></li>
            </ul>
        </nav>

        <section id="overview">
            <h2>1. Overview & Scope</h2>
            <p>Welcome to <strong>LocalVaddi</strong> ("we", "our", or "the App"). LocalVaddi is a smart loan ledger, Vaddi interest calculator, and collection management application designed to help money lenders, small business owners, and individuals manage interest calculations, principal repayments, borrower contact records, and collection schedules.</p>
            <p>Your privacy is of utmost importance to us. This Privacy Policy explains how LocalVaddi collects, uses, stores, and protects your personal and financial information when you use our mobile application and related services.</p>
        </section>

        <section id="information-collected">
            <h2>2. Information We Collect</h2>
            <p>Depending on how you use LocalVaddi, we may collect and process the following categories of information:</p>

            <h3>A. Information You Provide Directly</h3>
            <ul>
                <li><strong>Borrower & Lender Information:</strong> Names, phone numbers, contact addresses, and custom notes added to entries.</li>
                <li><strong>Financial & Transaction Records:</strong> Loan principal amounts, monthly/annual Vaddi interest rates (rupees per 100 per month or percentage), start and end dates, payment history, and collection statuses.</li>
                <li><strong>Account Credentials:</strong> If you choose to enable Cloud Sync or Google Sign-In, we collect your email address, profile name, and account identifiers provided by Google Authentication.</li>
            </ul>

            <h3>B. Automatically Collected Information</h3>
            <ul>
                <li><strong>Device Push Notification Tokens:</strong> Firebase Cloud Messaging (FCM) tokens to deliver payment reminders, collection alerts, and status updates.</li>
                <li><strong>System & Sync Status:</strong> Network connectivity state to manage offline queueing and background database synchronization.</li>
            </ul>

            <h3>C. Information accessed locally on your device</h3>
            <ul>
                <li><strong>Contacts List (Optional):</strong> When selecting a borrower from your address book, the app accesses contact details locally to fill borrower details. Your contact list is never uploaded to any external ad networks or third-party servers.</li>
            </ul>
        </section>

        <section id="how-we-use-data">
            <h2>3. How We Use Your Data</h2>
            <p>We use the collected information solely for core application features and operational purposes, including:</p>
            <ul>
                <li>Calculating accurate simple and compound interest (Vaddi calculation per ₹100 per month or annum).</li>
                <li>Maintaining loan ledgers, customer transaction histories, and repayment status logs.</li>
                <li>Sending daily collection reminders, notification alerts, and repayment due notifications.</li>
                <li>Providing optional cross-device cloud synchronization and encrypted cloud backups via Supabase.</li>
                <li>Authenticating user logins via Google Sign-In.</li>
            </ul>
        </section>

        <section id="permissions">
            <h2>4. App Permissions & Purpose</h2>
            <p>LocalVaddi requests Android system permissions only when necessary for specific features:</p>

            <div class="permission-box">
                <span class="permission-title">READ_CONTACTS (Optional)</span>
                <p>Allows you to select borrowers or lenders directly from your phone address book when creating a loan entry. Contact data is processed locally on your device.</p>
            </div>

            <div class="permission-box">
                <span class="permission-title">POST_NOTIFICATIONS</span>
                <p>Used to send daily collection reminders, interest calculation alerts, and system notifications.</p>
            </div>

            <div class="permission-box">
                <span class="permission-title">USE_BIOMETRIC / USE_FINGERPRINT / USE_FACE</span>
                <p>Enables local app locking using your device's biometric authentication (fingerprint or face unlock) for enhanced security.</p>
            </div>

            <div class="permission-box">
                <span class="permission-title">ACCESS_FINE_LOCATION / ACCESS_COARSE_LOCATION (Optional)</span>
                <p>Allows tagging collection locations or transaction locations on map entries when explicitly enabled by you.</p>
            </div>

            <div class="permission-box">
                <span class="permission-title">INTERNET & ACCESS_NETWORK_STATE</span>
                <p>Required for Google Sign-In authentication, Supabase cloud synchronization, and receiving push notifications.</p>
            </div>
        </section>

        <section id="storage-security">
            <h2>5. Data Storage & Security</h2>
            <p>We employ a <strong>Local-First Architecture</strong> combined with robust encryption practices:</p>
            <ul>
                <li><strong>Local Storage:</strong> Primary transaction and borrower data is stored in a local SQLite database (Android Room) on your device.</li>
                <li><strong>Cloud Synchronization (Optional):</strong> When cloud sync is enabled, data is transmitted over TLS/HTTPS encrypted channels to Supabase. Supabase uses Row Level Security (RLS) to ensure only your authenticated account can view or modify your data.</li>
                <li><strong>Biometric Security:</strong> Local app security is managed directly by Android OS BiometricPrompt APIs. Biometric hashes or raw fingerprint data are processed entirely by hardware security modules on your device and are never accessible to or stored by LocalVaddi.</li>
            </ul>
        </section>

        <section id="third-party-services">
            <h2>6. Third-Party Services</h2>
            <p>The App integrates with trustworthy third-party service providers for authentication, database synchronization, and push notifications:</p>
            <ul>
                <li><strong>Google Sign-In / Identity Services:</strong> Used for secure account login. <a href="https://policies.google.com/privacy" target="_blank" rel="noopener">Google Privacy Policy</a></li>
                <li><strong>Supabase:</strong> Provides backend authentication and database sync infrastructure. <a href="https://supabase.com/privacy" target="_blank" rel="noopener">Supabase Privacy Policy</a></li>
                <li><strong>Firebase Cloud Messaging (FCM):</strong> Used to deliver push notifications. <a href="https://policies.google.com/privacy" target="_blank" rel="noopener">Google Firebase Privacy Policy</a></li>
            </ul>
        </section>

        <section id="data-sharing">
            <h2>7. Data Sharing & Disclosure</h2>
            <p><strong>We DO NOT sell, rent, trade, or monetize your personal or financial data.</strong></p>
            <p>Your financial records, borrower details, and calculation history are strictly confidential and will never be shared with advertisers or third-party marketers. We will only disclose information if legally compelled by applicable laws, legal processes, or enforceable governmental requests.</p>
        </section>

        <section id="user-rights">
            <h2>8. Your Rights & Data Erasure</h2>
            <p>You retain complete control over your data:</p>
            <ul>
                <li><strong>Data Access & Export:</strong> You can view all recorded transactions within the app at any time and export backups.</li>
                <li><strong>Local Data Removal:</strong> Clearing app data or uninstalling the app permanently removes local records from your device.</li>
                <li><strong>Cloud Account Deletion:</strong> You can delete your cloud account and all synchronized records via the App Settings page, or submit a deletion request directly to our support email.</li>
            </ul>
        </section>

        <section id="biometrics">
            <h2>9. Biometrics & Device Security</h2>
            <p>LocalVaddi allows you to enable Biometric or PIN protection to prevent unauthorized access to your loan records. Biometric verification is handled entirely by the Android Operating System. No biometric templates, fingerprints, or facial data are ever saved, stored, or transmitted by our App.</p>
        </section>

        <section id="childrens-privacy">
            <h2>10. Children's Privacy</h2>
            <p>LocalVaddi is designed for adult financial management and is not intended for use by individuals under the age of 18. We do not knowingly collect personal information from children under 13 years of age.</p>
        </section>

        <section id="policy-changes">
            <h2>11. Changes to This Privacy Policy</h2>
            <p>We may update this Privacy Policy from time to time to reflect app updates, security enhancements, or legal compliance updates. Changes become effective immediately upon posting the updated policy page. We encourage you to review this page periodically.</p>
        </section>

        <section id="contact-us">
            <h2>12. Contact Information</h2>
            <p>If you have any questions, concerns, or data erasure requests regarding this Privacy Policy or LocalVaddi, please contact us at:</p>

            <div class="contact-card">
                <p><strong>Application:</strong> LocalVaddi</p>
                <p><strong>Developer Support Email:</strong> <a href="mailto:leelakrishna.pt369@gmail.com">leelakrishna.pt369@gmail.com</a></p>
                <p><strong>GitHub Repository:</strong> <span class="link-placeholder">[Your GitHub Repository Link Will Go Here]</span></p>
            </div>
        </section>
    </div>

    <footer>
        <p>&copy; 2026 LocalVaddi. All Rights Reserved. Designed for Money Lenders & Financial Calculation Management.</p>
    </footer>
</div>

</body>
</html>
