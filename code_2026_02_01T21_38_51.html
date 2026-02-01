
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>EOS - End of Shift Report</title>
    <style>
        body { font-family: Arial, sans-serif; background: #f5f5f5; padding: 20px; margin: 0; }
        .container { max-width: 900px; margin: 0 auto; background: white; padding: 30px; border-radius: 8px; box-shadow: 0 2px 10px rgba(0,0,0,0.1); }
        .header { background: #232F3E; color: white; padding: 20px; margin: -30px -30px 30px -30px; border-radius: 8px 8px 0 0; }
        .header h1 { margin: 0 0 15px 0; font-size: 24px; }
        .header-info { display: grid; grid-template-columns: repeat(2, 1fr); gap: 10px; font-size: 14px; }
        .section { margin-bottom: 30px; padding-left: 15px; border-left: 4px solid #FF9900; }
        .section-title { color: #232F3E; font-size: 18px; font-weight: bold; margin-bottom: 15px; }
        .metrics-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(160px, 1fr)); gap: 15px; margin: 15px 0; }
        .metric-card { background: #f9f9f9; padding: 15px; border-radius: 5px; border: 1px solid #ddd; text-align: center; }
        .metric-label { font-size: 11px; color: #666; text-transform: uppercase; margin-bottom: 8px; }
        .metric-value { font-size: 28px; font-weight: bold; color: #232F3E; }
        .metric-positive { color: #067D62; }
        .metric-warning { color: #D13212; }
        .highlight-box { background: #E8F4F8; padding: 15px; border-radius: 5px; margin: 15px 0; }
        .warning-box { background: #FFF3CD; padding: 15px; border-radius: 5px; margin: 10px 0; border-left: 3px solid #FFC107; }
        .action-box { background: #D1ECF1; padding: 15px; border-radius: 5px; margin: 10px 0; border-left: 3px solid #17A2B8; }
        table { width: 100%; border-collapse: collapse; margin: 15px 0; }
        th, td { padding: 12px; text-align: left; border-bottom: 1px solid #ddd; }
        th { background: #f0f0f0; font-weight: bold; color: #232F3E; }
        ul { margin: 10px 0; padding-left: 25px; }
        li { margin: 8px 0; }
        .status-badge { display: inline-block; padding: 4px 10px; border-radius: 3px; font-size: 11px; font-weight: bold; margin-left: 10px; }
        .status-completed { background: #D4EDDA; color: #155724; }
        .status-pending { background: #FFF3CD; color: #856404; }
        .footer { margin-top: 40px; padding-top: 20px; border-top: 2px solid #ddd; text-align: center; font-size: 12px; color: #666; }
        h3 { color: #232F3E; font-size: 16px; margin: 15px 0 10px 0; }
        input[type="text"], input[type="number"], input[type="date"], input[type="email"], textarea, select {
            width: 100%; padding: 8px; border: 1px solid #ddd; border-radius: 4px; font-family: Arial, sans-serif; font-size: 14px; box-sizing: border-box;
        }
        input[type="text"]:focus, input[type="number"]:focus, input[type="date"]:focus, textarea:focus, select:focus {
            outline: none; border-color: #FF9900; box-shadow: 0 0 5px rgba(255, 153, 0, 0.3);
        }
        textarea { min-height: 80px; resize: vertical; }
        .input-group { margin: 10px 0; }
        .input-label { font-weight: bold; color: #232F3E; margin-bottom: 5px; display: block; font-size: 13px; }
        .inline-input { display: inline-block; width: auto; min-width: 100px; margin: 0 5px; }
        .btn-container { text-align: center; margin: 30px 0; position: sticky; bottom: 20px; background: white; padding: 15px; border-radius: 8px; box-shadow: 0 -2px 10px rgba(0,0,0,0.1); }
        .btn { background: #FF9900; color: white; border: none; padding: 12px 25px; font-size: 15px; border-radius: 5px; cursor: pointer; margin: 5px; transition: all 0.3s; }
        .btn:hover { background: #EC7211; transform: translateY(-2px); box-shadow: 0 4px 8px rgba(0,0,0,0.2); }
        .btn-secondary { background: #232F3E; }
        .btn-secondary:hover { background: #131921; }
        .btn-success { background: #067D62; }
        .btn-success:hover { background: #055a47; }
        .editable-table td input { width: 80px; padding: 5px; }
        .share-section { background: #E8F4F8; padding: 20px; border-radius: 8px; margin: 20px 0; text-align: center; }
        .share-link { background: white; padding: 10px; border: 1px solid #ddd; border-radius: 4px; margin: 10px 0; word-break: break-all; font-family: monospace; font-size: 12px; max-height: 100px; overflow-y: auto; }
        .email-modal { display: none; position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.5); z-index: 1000; }
        .email-modal-content { background: white; margin: 10% auto; padding: 30px; border-radius: 8px; max-width: 500px; box-shadow: 0 4px 20px rgba(0,0,0,0.3); }
        .email-modal-header { font-size: 20px; font-weight: bold; color: #232F3E; margin-bottom: 20px; }
        .close-modal { float: right; font-size: 28px; font-weight: bold; color: #666; cursor: pointer; }
        .close-modal:hover { color: #000; }
        @media print {
            body { background: white; padding: 0; }
            .container { box-shadow: none; }
            .btn-container, .share-section, .email-modal { display: none; }
            input, textarea, select { border: none; background: transparent; padding: 0; }
        }
    </style>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2pdf.js/0.10.1/html2pdf.bundle.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js"></script>
</head>
<body>
    <div class="container" id="reportContent">
        <div class="header">
            <h1>EOS - End of Shift Report</h1>
            <div class="header-info">
                <div><strong>Date:</strong> <input type="date" class="inline-input" id="fecha" value="2026-02-01"></div>
                <div><strong>Shift:</strong> <input type="text" class="inline-input" id="turno" value="Day Shift"></div>
                <div><strong>Shift Manager:</strong> <input type="text" class="inline-input" id="manager" placeholder="Your name"></div>
                <div><strong>Site:</strong> <input type="text" class="inline-input" id="site" placeholder="Your site"></div>
            </div>
        </div>

        <div class="section">
            <div class="section-title">1. SAFETY</div>
            <div class="highlight-box">
                <div class="input-group">
                    <label class="input-label">Status:</label>
                    <select id="safetyStatus">
                        <option value="No incidents">No incidents</option>
                        <option value="Incident reported">Incident reported</option>
                    </select>
                </div>
                <div class="input-group">
                    <label class="input-label">Austin ID:</label>
                    <input type="text" id="austinId" placeholder="N/A or case number" value="N/A">
                </div>
                <div class="input-group">
                    <label class="input-label">Description (if applicable):</label>
                    <textarea id="safetyDesc" placeholder="Describe incident if applicable"></textarea>
                </div>
            </div>
        </div>

        <div class="section">
            <div class="section-title">2. CAPACITY METRICS</div>
            <div class="metrics-grid">
                <div class="metric-card">
                    <div class="metric-label">Total ALPS Capacity</div>
                    <div class="metric-value"><input type="number" class="inline-input" id="alpsCapacity" value="17786" style="width: 100px;"></div>
                    <small>units</small>
                </div>
                <div class="metric-card">
                    <div class="metric-label">Adjusted Capacity</div>
                    <div class="metric-value"><input type="number" class="inline-input" id="adjCapacity" value="14090" style="width: 100px;"></div>
                    <small>units/day</small>
                </div>
                <div class="metric-card">
                    <div class="metric-label">Target TPH</div>
                    <div class="metric-value"><input type="number" class="inline-input" id="targetTPH" value="20" style="width: 80px;"></div>
                </div>
                <div class="metric-card">
                    <div class="metric-label">Active Headcount</div>
                    <div class="metric-value"><input type="number" class="inline-input" id="headcount" value="62" style="width: 80px;"></div>
                    <small>AA</small>
                </div>
            </div>
            <div class="input-group">
                <label class="input-label">Adjustments made:</label>
                <textarea id="adjustments" placeholder="E.g., LS MTY1 cancellation">LS MTY1 cancellation</textarea>
            </div>
        </div>

        <div class="section">
            <div class="section-title">3. FINAL RESULTS</div>
            <div class="metrics-grid">
                <div class="metric-card">
                    <div class="metric-label">Processed Units</div>
                    <div class="metric-value metric-positive"><input type="number" class="inline-input" id="processedUnits" value="15210" style="width: 100px;"></div>
                </div>
                <div class="metric-card">
                    <div class="metric-label">% VS PLAN</div>
                    <div class="metric-value metric-positive"><input type="number" class="inline-input" id="vsPlan" value="107" style="width: 80px;">%</div>
                </div>
                <div class="metric-card">
                    <div class="metric-label">Fast Start TP90</div>
                    <div class="metric-value"><input type="number" class="inline-input" id="fastStart" value="20" style="width: 80px;"></div>
                    <small>min</small>
                </div>
                <div class="metric-card">
                    <div class="metric-label">Achieved TPH</div>
                    <div class="metric-value"><input type="number" class="inline-input" id="achievedTPH" value="19" style="width: 80px;"></div>
                </div>
                <div class="metric-card">
                    <div class="metric-label">Productivity</div>
                    <div class="metric-value metric-positive"><input type="number" class="inline-input" id="productivity" value="111" style="width: 80px;">%</div>
                </div>
                <div class="metric-card">
                    <div class="metric-label">Late Departure</div>
                    <div class="metric-value metric-warning"><input type="number" class="inline-input" id="lateDeparture" value="2" style="width: 80px;"></div>
                </div>
                <div class="metric-card">
                    <div class="metric-label">Late Slam</div>
                    <div class="metric-value metric-warning"><input type="number" class="inline-input" id="lateSlam" value="4" style="width: 80px;"></div>
                </div>
            </div>
            <div class="warning-box">
                <label class="input-label">Pending Items:</label>
                <textarea id="pendingItems" placeholder="List pending items">1 ATROP not processed in SLAM</textarea>
            </div>
        </div>

        <div class="section">
            <div class="section-title">4. STAFF DISTRIBUTION AND TRAINING</div>
            <h3>A. Skill Drills Completed:</h3>
            <table class="editable-table">
                <tr><th>Area</th><th>Associates</th></tr>
                <tr><td>Pick</td><td><input type="number" id="pickDrill" value="20"></td></tr>
                <tr><td>Rebin</td><td><input type="number" id="rebinDrill" value="4"></td></tr>
                <tr><td>Pack</td><td><input type="number" id="packDrill" value="3"></td></tr>
                <tr><td>Dock</td><td><input type="number" id="dockDrill" value="3"></td></tr>
            </table>
            <h3>B. Support Staff:</h3>
            <div class="input-group">
                <label class="input-label">Active ambassadors:</label>
                <input type="number" id="ambassadors" value="4">
            </div>
            <h3>C. Scheduled Training:</h3>
            <div class="input-group">
                <label class="input-label">Training details:</label>
                <textarea id="trainingDetails" placeholder="Time, type, participants">09:30 - 1 NH training in dock
5 AA in dock training (10:00-15:00)</textarea>
            </div>
        </div>

        <div class="section">
            <div class="section-title">5. QUALITY MANAGEMENT</div>
            <h3>A. SUM Meetings Conducted:</h3>
            <div class="input-group">
                <label class="input-label">Location and time:</label>
                <input type="text" id="sumLocation" placeholder="E.g., Pick Mod - 13:00" value="Pick Mod - 13:00">
            </div>
            <div class="input-group">
                <label class="input-label">Topics covered:</label>
                <textarea id="sumTopics" placeholder="List topics discussed">- Use of visual aids
- ASIN prioritization
- Procedures: Idle time, Fast start, Strong finish</textarea>
            </div>
            <h3>B. Identified Barriers:</h3>
            <div class="warning-box">
                <textarea id="barriers" placeholder="List identified barriers">- Inadequate ladder location
- Bathroom access issues
- Confusing aisle numbering
- Open and/or full drawers
- Lack of radios for reporting
- Cleaning staff access restrictions</textarea>
            </div>
        </div>

        <div class="section">
            <div class="section-title">6. QUALITY METRICS</div>
            <table class="editable-table">
                <tr><th>Metric</th><th>Detected Errors</th><th>DPMO</th><th>Target</th></tr>
                <tr>
                    <td>Wrong ASIN</td>
                    <td><input type="number" id="wrongAsin" value="292"></td>
                    <td><input type="number" id="wrongAsinDPMO" placeholder="Calculate"></td>
                    <td><input type="number" id="wrongAsinTarget" placeholder="Target"></td>
                </tr>
                <tr>
                    <td>Failed Moves</td>
                    <td><input type="number" id="failedMoves" value="150"></td>
                    <td><input type="number" id="failedMovesDPMO" placeholder="Calculate"></td>
                    <td><input type="number" id="failedMovesTarget" placeholder="Target"></td>
                </tr>
            </table>
            <div class="input-group">
                <label class="input-label">Root Cause:</label>
                <textarea id="rootCause" placeholder="Describe the main root cause of deviations"></textarea>
            </div>
        </div>

        <div class="section">
            <div class="section-title">7. ACTION PLAN</div>
            <h3>A. Immediate Actions:</h3>
            <div class="input-group">
                <label class="input-label">Completed or in-progress actions:</label>
                <textarea id="immediateActions" placeholder="List actions with owner and status">✓ Ladder relocation - Completed (Night Shift, to be shared in SUM)
⏳ Coordination with cleaning team - In Progress
⏳ Reinforcement of care protocols - Pending</textarea>
            </div>
            <h3>B. Medium-term Actions:</h3>
            <div class="input-group">
                <textarea id="mediumActions" placeholder="List actions with timeline">- Implementation of daily SUM in pick mod (Starting next week)
- Creation of specific auditor role for container auditing and package investigation (To be defined)</textarea>
            </div>
        </div>

        <div class="section">
            <div class="section-title">8. FOLLOW-UP</div>
            <div class="highlight-box">
                <label class="input-label">Critical Hand-offs for Next Shift:</label>
                <textarea id="handoffs" placeholder="List critical hand-offs">- Communication of changes in next day's SUM
- Monitoring of new cleaning protocols
- Supervision of damage reports
- Dual reporting system: Scanner Andons + Direct communication with AM</textarea>
            </div>
        </div>

        <div class="section">
            <div class="section-title">9. FOCUS AREAS FOR NEXT SHIFT</div>
            <div class="input-group">
                <textarea id="focusAreas" placeholder="List priorities for next shift">Priority 1: Monitoring of action implementation
Priority 2: Training follow-up
Priority 3: Verification of improvements in identified areas</textarea>
            </div>
        </div>

        <div class="footer">
            <p>This report was generated on <span id="currentDate"></span></p>
            <p>For questions or clarifications, contact <strong>vbojorqu</strong></p>
        </div>
    </div>

    <div class="share-section" id="shareSection" style="display:none;">
        <h3>🔗 Share Link</h3>
        <p>Copy this link to share the report with your team:</p>
        <div class="share-link" id="shareLink"></div>
        <button class="btn btn-success" onclick="copyShareLink()">📋 Copy Link</button>
    </div>

    <div class="email-modal" id="emailModal">
        <div class="email-modal-content">
            <span class="close-modal" onclick="closeEmailModal()">&times;</span>
            <div class="email-modal-header">📧 Send EOS via Email</div>
            <div class="input-group">
                <label class="input-label">To (comma-separated emails):</label>
                <input type="email" id="emailTo" placeholder="example@amazon.com, other@amazon.com" multiple>
            </div>
            <div class="input-group">
                <label class="input-label">Subject:</label>
                <input type="text" id="emailSubject" value="">
            </div>
            <div class="input-group">
                <label class="input-label">CC (optional):</label>
                <input type="email" id="emailCC" placeholder="cc@amazon.com">
            </div>
            <div style="text-align: center; margin-top: 20px;">
                <button class="btn" onclick="sendEmail()">📤 Send Email</button>
                <button class="btn btn-secondary" onclick="closeEmailModal()">Cancel</button>
            </div>
        </div>
    </div>

    <div class="btn-container">
        <button class="btn" onclick="exportToPDF()">📄 Export to PDF</button>
        <button class="btn" onclick="exportAsImage()">🖼️ Export as Image</button>
        <button class="btn" onclick="openEmailModal()">📧 Send via Email</button>
        <button class="btn btn-success" onclick="generateShareLink()">🔗 Generate Share Link</button>
        <button class="btn btn-secondary" onclick="window.print()">🖨️ Print</button>
        <button class="btn btn-secondary" onclick="resetForm()">🔄 Clear Form</button>
    </div>

    <script>
        document.getElementById('currentDate').textContent = new Date().toLocaleDateString('en-US');
        
        function updateEmailSubject() {
            const fecha = document.getElementById('fecha').value;
            const turno = document.getElementById('turno').value;
            const site = document.getElementById('site').value;
            document.getElementById('emailSubject').value = `EOS Report - ${site} - ${turno} - ${fecha}`;
        }
        
        function exportToPDF() {
            const element = document.getElementById('reportContent');
            const opt = {
                margin: 10,
                filename: 'EOS_Report_' + document.getElementById('fecha').value + '.pdf',
                image: { type: 'jpeg', quality: 0.98 },
                html2canvas: { scale: 2 },
                jsPDF: { unit: 'mm', format: 'a4', orientation: 'portrait' }
            };
            
            html2pdf().set(opt).from(element).save().then(() => {
                alert('✅ PDF exported successfully!');
            });
        }
        
        function exportAsImage() {
            const element = document.getElementById('reportContent');
            html2canvas(element, { scale: 2 }).then(canvas => {
                canvas.toBlob(blob => {
                    const url = URL.createObjectURL(blob);
                    const link = document.createElement('a');
                    link.download = 'EOS_Report_' + document.getElementById('fecha').value + '.png';
                    link.href = url;
                    link.click();
                    alert('✅ Image exported successfully!');
                });
            });
        }
        
        function openEmailModal() {
            updateEmailSubject();
            document.getElementById('emailModal').style.display = 'block';
        }
        
        function closeEmailModal() {
            document.getElementById('emailModal').style.display = 'none';
        }
        
        function sendEmail() {
            const emailTo = document.getElementById('emailTo').value;
            const emailSubject = document.getElementById('emailSubject').value;
            const emailCC = document.getElementById('emailCC').value;
            
            if (!emailTo) {
                alert('⚠️ Please enter at least one recipient');
                return;
            }
            
            let mailtoLink = `mailto:${emailTo}?subject=${encodeURIComponent(emailSubject)}`;
            
            if (emailCC) {
                mailtoLink += `&cc=${encodeURIComponent(emailCC)}`;
            }
            
            const bodyText = `EOS Report - ${document.getElementById('fecha').value}

Please see the attached report or shared link.

Contact: vbojorqu`;
            mailtoLink += `&body=${encodeURIComponent(bodyText)}`;
            
            window.location.href = mailtoLink;
            
            copyToClipboard();
            
            alert('✅ Your email client will open. The report content is copied to clipboard - paste it (Ctrl+V) into the email body.');
            
            closeEmailModal();
        }
        
        function copyToClipboard() {
            const content = document.getElementById('reportContent');
            const range = document.createRange();
            range.selectNode(content);
            window.getSelection().removeAllRanges();
            window.getSelection().addRange(range);
            document.execCommand('copy');
            window.getSelection().removeAllRanges();
        }
        
        function generateShareLink() {
            try {
                const data = collectFormData();
                const jsonString = JSON.stringify(data);
                const encodedData = btoa(unescape(encodeURIComponent(jsonString)));
                const baseUrl = window.location.href.split('?')[0];
                const shareUrl = baseUrl + '?data=' + encodedData;
                
                document.getElementById('shareLink').textContent = shareUrl;
                document.getElementById('shareSection').style.display = 'block';
                document.getElementById('shareSection').scrollIntoView({ behavior: 'smooth' });
            } catch (error) {
                alert('⚠️ Error generating link: ' + error.message);
            }
        }
        
        function copyShareLink() {
            const linkText = document.getElementById('shareLink').textContent;
            navigator.clipboard.writeText(linkText).then(() => {
                alert('✅ Link copied to clipboard. Share it with your team.');
            }).catch(err => {
                const textArea = document.createElement('textarea');
                textArea.value = linkText;
                document.body.appendChild(textArea);
                textArea.select();
                document.execCommand('copy');
                document.body.removeChild(textArea);
                alert('✅ Link copied to clipboard. Share it with your team.');
            });
        }
        
        function collectFormData() {
            return {
                fecha: document.getElementById('fecha').value,
                turno: document.getElementById('turno').value,
                manager: document.getElementById('manager').value,
                site: document.getElementById('site').value,
                safetyStatus: document.getElementById('safetyStatus').value,
                austinId: document.getElementById('austinId').value,
                safetyDesc: document.getElementById('safetyDesc').value,
                alpsCapacity: document.getElementById('alpsCapacity').value,
                adjCapacity: document.getElementById('adjCapacity').value,
                targetTPH: document.getElementById('targetTPH').value,
                headcount: document.getElementById('headcount').value,
                adjustments: document.getElementById('adjustments').value,
                processedUnits: document.getElementById('processedUnits').value,
                vsPlan: document.getElementById('vsPlan').value,
                fastStart: document.getElementById('fastStart').value,
                achievedTPH: document.getElementById('achievedTPH').value,
                productivity: document.getElementById('productivity').value,
                lateDeparture: document.getElementById('lateDeparture').value,
                lateSlam: document.getElementById('lateSlam').value,
                pendingItems: document.getElementById('pendingItems').value,
                pickDrill: document.getElementById('pickDrill').value,
                rebinDrill: document.getElementById('rebinDrill').value,
                packDrill: document.getElementById('packDrill').value,
                dockDrill: document.getElementById('dockDrill').value,
                ambassadors: document.getElementById('ambassadors').value,
                trainingDetails: document.getElementById('trainingDetails').value,
                sumLocation: document.getElementById('sumLocation').value,
                sumTopics: document.getElementById('sumTopics').value,
                barriers: document.getElementById('barriers').value,
                wrongAsin: document.getElementById('wrongAsin').value,
                wrongAsinDPMO: document.getElementById('wrongAsinDPMO').value,
                wrongAsinTarget: document.getElementById('wrongAsinTarget').value,
                failedMoves: document.getElementById('failedMoves').value,
                failedMovesDPMO: document.getElementById('failedMovesDPMO').value,
                failedMovesTarget: document.getElementById('failedMovesTarget').value,
                rootCause: document.getElementById('rootCause').value,
                immediateActions: document.getElementById('immediateActions').value,
                mediumActions: document.getElementById('mediumActions').value,
                handoffs: document.getElementById('handoffs').value,
                focusAreas: document.getElementById('focusAreas').value
            };
        }
        
        function loadFormData(data) {
            Object.keys(data).forEach(key => {
                const element = document.getElementById(key);
                if (element) {
                    element.value = data[key];
                }
            });
        }
        
        function resetForm() {
            if (confirm('Are you sure you want to clear all fields?')) {
                document.querySelectorAll('input[type="text"], input[type="number"], input[type="email"], textarea').forEach(input => {
                    if (!input.id.includes('fecha') && !input.id.includes('turno')) {
                        input.value = '';
                    }
                });
            }
        }
        
        window.onload = function() {
            const urlParams = new URLSearchParams(window.location.search);
            const encodedData = urlParams.get('data');
            if (encodedData) {
                try {
                    const jsonString = decodeURIComponent(escape(atob(encodedData)));
                    const data = JSON.parse(jsonString);
                    loadFormData(data);
                } catch (e) {
                    console.error('Error loading shared data:', e);
                }
            }
        };
        
        window.onclick = function(event) {
            const modal = document.getElementById('emailModal');
            if (event.target == modal) {
                closeEmailModal();
            }
        }
    </script>
</body>
</html>

