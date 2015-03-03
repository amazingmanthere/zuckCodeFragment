open music tracks mode：
	
	// play sounds regardless of whether device is silent or not 
    AVAudioSession *session = [AVAudioSession sharedInstance];
    [session setCategory:AVAudioSessionCategoryPlayback error:nil];