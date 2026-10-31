<!-- ... existing code ... -->
        /* Document Watermark Styling */
        .usms-watermark {
            position: relative;
        }
        .usms-watermark-bg {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            width: 82%;
            height: auto;
            max-height: 85%;
            object-fit: contain;
            pointer-events: none;
            z-index: 0;
            opacity: 0.85;
        }

        .document-grid {
            border: 2px solid #000;
        }
<!-- ... existing code ... -->
                        <!-- Subheader Titles -->
                        <div class="text-center my-4 py-2 border-y-2 border-black">
                            <h2 class="font-bold text-lg tracking-wider text-black uppercase">RACK ONE COMPUTING | MOBILE DATA CENTER</h2>
                            <h3 class="font-bold text-sm tracking-wide text-black uppercase mt-0.5">FACIAL RECOGNITION & LABORATORY RECORD</h3>
                        </div>

                        <!-- Grid 2x2 with Watermark Seal -->
                        <div class="usms-watermark document-grid grid grid-cols-2 mt-4 relative z-10">
                            <img src="image_a6b860.png" alt="USMS IOD Official Seal" class="usms-watermark-bg">
                            
                            <!-- Box 1: DATA BASE -->
                            <div class="p-4 flex flex-col justify-between border-black min-h-[320px] relative z-10 bg-white/70">
                                <div>
                                    <h3 class="font-bold text-base underline mb-3 text-center uppercase tracking-wide">DATA BASE</h3>
<!-- ... existing code ... -->
                            <!-- Box 2: IMAGEN DATABASE -->
                            <div class="p-4 flex flex-col items-center justify-between border-black min-h-[320px] relative z-10 bg-white/70">
                                <h3 class="font-bold text-base underline mb-2 text-center uppercase tracking-wide w-full">IMAGEN DATABASE</h3>
                                <div class="flex-1 w-full flex items-center justify-center p-2 bg-slate-50/80 border border-slate-200 rounded">
                                    <img id="previewFotoSospechoso" src="" alt="Foto Sospechoso" class="max-h-[240px] max-w-full object-contain hidden shadow-sm">
                                    <div id="placeholderFotoSospechoso" class="text-center text-slate-400 text-xs italic">
                                        <i class="fa-solid fa-user-tie text-4xl block mb-2 opacity-30"></i>
                                        [ FOTO DEL SOSPECHOSO ]
                                    </div>
                                </div>
                            </div>

                            <!-- Box 3: Observaciones -->
                            <div class="p-4 flex flex-col justify-between border-black min-h-[320px] relative z-10 bg-white/70">
                                <div>
                                    <h3 class="font-bold text-base underline mb-3 text-center uppercase tracking-wide">Observaciones</h3>
                                    <p class="font-bold text-sm mb-2 flex items-center gap-1">
                                        <span>➔</span> <span>Características Físicas:</span>
                                    </p>
                                    <ul class="space-y-2 text-sm pl-4">
                                        <li class="flex"><span class="w-36 font-semibold">- Tatuajes:</span> <span id="displayTatuajes" class="font-normal flex-1 border-b border-dashed border-slate-400 min-h-[20px]"></span></li>
                                        <li class="flex"><span class="w-36 font-semibold">- Tez:</span> <span id="displayTez" class="font-normal flex-1 border-b border-dashed border-slate-400 min-h-[20px]"></span></li>
                                        <li class="flex"><span class="w-36 font-semibold">- Fisiología:</span> <span id="displayFisiologia" class="font-normal flex-1 border-b border-dashed border-slate-400 min-h-[20px]"></span></li>
                                        <li class="flex"><span class="w-36 font-semibold">- Contextura Física:</span> <span id="displayContextura" class="font-normal flex-1 border-b border-dashed border-slate-400 min-h-[20px]"></span></li>
                                    </ul>
                                </div>
                            </div>

                            <!-- Box 4: EVIDENCIA LABORATORIO -->
                            <div class="p-4 flex flex-col items-center justify-between border-black min-h-[320px] relative z-10 bg-white/70">
                                <h3 class="font-bold text-base underline mb-2 text-center uppercase tracking-wide w-full">EVIDENCIA LABORATORIO</h3>
                                <div class="flex-1 w-full flex items-center justify-center p-2 bg-slate-50/80 border border-slate-200 rounded">
                                    <img id="previewFotoEvidencia" src="" alt="Evidencia Laboratorio" class="max-h-[240px] max-w-full object-contain hidden shadow-sm">
                                    <div id="placeholderFotoEvidencia" class="text-center text-slate-400 text-xs italic">
                                        <i class="fa-solid fa-microscope text-4xl block mb-2 opacity-30"></i>
                                        [ EVIDENCIA DE LABORATORIO ]
                                    </div>
                                </div>
                            </div>

                        </div>
                    </div>
<!-- ... existing code ... -->