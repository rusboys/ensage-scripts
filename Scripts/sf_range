Range1 = 200
Range2 = 450
Range3 = 700

function Checkname( name )
	if me.name == "Nevermore" then
		DrawRange()
	end
end

function GameStart()
	DrawRange()
end

function DrawRange()
			local eff = Effect(me,"range_display")
			local eff1 = Effect(me,"range_display")
			local eff2 = Effect(me,"range_display")
			eff:SetParameter( Vector(Range1,0,0) )
			eff1:SetParameter( Vector(Range2,0,0) )
			eff2:SetParameter( Vector(Range3,0,0) )
		end


script:RegisterEvent(EVENT_START,GameStart)

if me then
	DrawRange()
end
