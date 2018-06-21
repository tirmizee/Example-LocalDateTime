# Example-LocalDateTime

    	LocalDateTime plusDays = LocalDateTime.now().plusDays(1);
		System.out.println("plusDays " + plusDays);
		
		LocalDateTime plusHours = LocalDateTime.now().plusHours(2);
		System.out.println("plusHours " + plusHours);
		
		LocalDateTime plusMinutes = LocalDateTime.now().plusMinutes(20);
		System.out.println("plusMinutes " +plusMinutes);
		
		LocalDateTime plusMonths = LocalDateTime.now().plusMonths(1);
		System.out.println("plusMonths " + plusMonths);
		
		LocalDateTime plusSeconds = LocalDateTime.now().plusSeconds(59);
		System.out.println("plusSeconds " + plusSeconds);
		
		LocalDateTime plusWeeks = LocalDateTime.now().plusWeeks(2);
		System.out.println("plusWeeks " + plusWeeks);
		
		LocalDateTime plusYears = LocalDateTime.now().plusYears(2);
		System.out.println("plusYears " + plusYears);
		
		LocalDateTime plusNegativeDays = LocalDateTime.now().plusDays(-1);
		System.out.println("plusNegativeDays " + plusNegativeDays);
